---
sectionid: cmnDynam
title: "Dynamics in CMN"
version: "v4"
---

Common Music Notation provides two different methodologies for expressing the volume of a note, phrase, section, etc. The first is a verbal instruction providing such information in human language, possibly in an abbreviated form. An example is the word *piano*, indicating a quiet volume, often abbreviated as *p*. In MEI, verbal instructions like this are encoded using the {% include link elem="dynam" %} element from the Shared module (see chapter {% include link id="shared" %}):
{% include mei example="cmn/cmn-sample125.txt" valid="false" %}

By convention, {% include link elem="dynam" %} elements, like {% include link elem="slur" %} and other elements belonging to the {% include link model="controlEventLike" %} class, are encoded at the end of the {% include link elem="measure" %} to which they belong. This requires {% include link elem="dynam" %} to be assigned to a certain {% include link elem="staff" %} using the **@staff** attribute, whose value refers to the target element's **@n** attribute. In the absence of other information, all layers within the staff are assumed to have the same dynamic marking.

{% include mei example="cmn/cmn-sample126.txt" valid="true" %}

However, when the layers of a staff have different dynamic indications, the **@layer** attribute may be used to associate a dynamic marking with a particular layer:

{% include mei example="cmn/cmn-sample127.txt" valid="true" %}

A suitable MIDI value may be assigned to a dynamic marking using the **@val** attribute:

{% include mei example="cmn/cmn-sample128.txt" valid="true" %}

The location of a dynamic marking in relation to a staff may be specified using the **@place** attribute, which may be given as *above*, *within*, or *below* the staff:

{% include mei example="cmn/cmn-sample129.txt" valid="true" %}

Dynamics must also be associated with a particular time point in a measure, using the **@tstamp**, or with a particular event, using the **@startid** attribute. Linking a control event with measures and events is discussed in section {% include link id="cmnTstamp" %}:

{% include mei example="cmn/cmn-sample130.txt" valid="false" %}

Dynamics which do not have an explicit endpoint are often referred to as ‘instantaneous’. On the other hand, some dynamic directions indicate a continuous change that must have a defined end point. It is possible to specify the logical scope of continuous dynamic marks using the attributes **@tstamp2**, **@dur**, **@dur.ges**, or **@endid**. Additionally a corresponding ending value for MIDI output may be given in the **@val2** attribute.

To capture the fact that the *crescendo* in the example above continue until the first beat of the next measure, they may be marked:

{% include mei example="cmn/cmn-sample131.txt" valid="true" %}
{% include mei example="cmn/cmn-sample132.txt" valid="true" %}

Any combination of **@tstamp**, **@startid**, **@tstamp2**, and **@endid** attributes may be used to define the scope of a dynamic, although the **@tstamp** and **@tstamp2** or the **@startid** and **@endid** combinations are the most logical combinations. For example, the following alternatives are all possibilities for encoding up a crescendo. The choice of attributes is often task or processor dependent.

{% include mei example="cmn/cmn-sample133.txt" valid="true" %}
{% include mei example="cmn/cmn-sample134.txt" valid="true" %}
{% include mei example="cmn/cmn-sample135.txt" valid="true" %}
{% include mei example="cmn/cmn-sample136.txt" valid="true" %}

All musical elements affected by the {% include link elem="dynam" %} may be explicitly specified using the **@plist** attribute, which contains **@xml:id** attribute value references:

{% include mei example="cmn/cmn-sample137.txt" valid="true" %}

It is recommended that the list of references in **@plist** include all participants in the dynamic marking, including the first and last notes as in the preceding example, even though they are duplicated by **@startid** and **@endid** attributes.

In addition to verbal instructions, Common Music Notation uses graphical symbols to indicate ‘continuous’ dynamics. These crescendo and decrescendo (or diminuendo) symbols are encoded in MEI using the {% include link elem="hairpin" %} element. It also is a member of the {% include link model="controlEventLike" %} class, which means it too is used just before the close of a {% include link elem="measure" %} element, following the encoding of all staves. The required attribute **@form** specifies the direction of the symbol by taking one of two possible values: *cres* (growing louder) or *dim* (getting softer).

{% include mei example="cmn/cmn-sample138.txt" valid="false" %}

Marking the logical extent of hairpins is possible using the same attributes as for {% include link elem="dynam" %}.

{% include mei example="cmn/cmn-sample139.txt" valid="true" %}

The following example from [Béla Bartók's](https://en.wikipedia.org/wiki/B%C3%A9la_Bart%C3%B3k) *Mikrokosmos*, Sz.107 shows a *diminuendo* between two staves that begins on the first beat (in the current measure) and ends on the first one in the penultimate measure. The duration is highlighted with a dashed line, which can be indicated with the **@extender** attribute.

{% include figure img="ExampleImages/dynamics.1.png" caption="A diminuendo in Bartók's In Phrygian Mode" %}
{% include mei example="cmn/cmn-sample-dim.txt" valid="true" %}
