---
layout: sidebar
sidebar: s1
version: "v4"
title: "att.rehearsal"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.rehearsal">att.rehearsal</h3>
      <div class="specs">
         <div class="desc">Attributes used by scoreDef and staffDef to provide default information about rehearsal
            numbers/letters.
         </div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.cmn</div>
         </div>
         <div class="facet attributes" id="attributes">
            <div class="label">Attributes</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="attributes_compact_tab" href="#attributes" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="full" id="attributes_full_tab" href="#attributes" class="displayTab">full definition</a></li>
                  <li class="tab-item"><a data-display="class" id="attributes_class_tab" href="#attributes" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="attributes_module_tab" href="#attributes" class="displayTab">by module</a></li>
               </ul>
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident attribute" title="Describes the enclosing shape for rehearsal marks.">reh.enclose</span></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full">
                  <div class="attributeDef def" data-module="MEI.cmn"><span class="ident attribute" title="Describes the enclosing shape for rehearsal marks.">reh.enclose</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the enclosing shape for rehearsal marks.</span><span class="attributeValues">
                        Allowed values are:
                        "<span style="font-weight: 500;">box</span>" <i>(Enclosed by box.)</i>,  "<span style="font-weight: 500;">circle</span>" <i>(Enclosed by circle.)</i>,  "<span style="font-weight: 500;">none</span>" <i>(No enclosing shape.)</i></span></div>
               </div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox direct" title="direct childs">
                     <div class="classHeading"><label class="classLabel">direct childs</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.cmn"><span class="ident attribute" title="Describes the enclosing shape for rehearsal marks.">reh.enclose</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the enclosing shape for rehearsal marks.</span><span class="attributeValues">
                              Allowed values are:
                              "<span style="font-weight: 500;">box</span>" <i>(Enclosed by box.)</i>,  "<span style="font-weight: 500;">circle</span>" <i>(Enclosed by circle.)</i>,  "<span style="font-weight: 500;">none</span>" <i>(No enclosing shape.)</i></span></div>
                     </div>
                  </div>
               </div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.cmn">
                     <div class="classHeading"><label class="classLabel">MEI.cmn</label><span class="classDesc">Common Music Notation (CMN) repertoire component declarations.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.cmn"><span class="ident attribute" title="Describes the enclosing shape for rehearsal marks.">reh.enclose</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Describes the enclosing shape for rehearsal marks.</span><span class="attributeValues">
                              Allowed values are:
                              "<span style="font-weight: 500;">box</span>" <i>(Enclosed by box.)</i>,  "<span style="font-weight: 500;">circle</span>" <i>(Enclosed by circle.)</i>,  "<span style="font-weight: 500;">none</span>" <i>(No enclosing shape.)</i></span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet availableAt" id="availableAt">
            <div class="label">Available at</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="availableAt_compact_tab" href="#availableAt" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="class" id="availableAt_class_tab" href="#availableAt" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="availableAt_module_tab" href="#availableAt" class="displayTab">by module</a></li>
               </ul>
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="(score definition) – Container for score meta-information."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/scoredef.html">scoreDef</a></span>, <span class="ident element" title="(staff definition) – Container for staff meta-information."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/staffdef.html">staffDef</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.rehearsal">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.rehearsal.html">att.rehearsal</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="classBox" title="att.scoreDef.vis.cmn">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.scoredef.vis.cmn.html">att.scoreDef.vis.cmn</a></label><span class="classDesc"></span></div>
                           <div class="classContent">
                              <div class="classBox" title="att.scoreDef.vis">
                                 <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.scoredef.vis.html">att.scoreDef.vis</a></label><span class="classDesc"></span></div>
                                 <div class="classContent">
                                    <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/scoredef.html">scoreDef</a><span class="elementDesc">(score definition) – Container for score meta-information.</span></div>
                                 </div>
                              </div>
                           </div>
                        </div>
                        <div class="classBox" title="att.staffDef.vis.cmn">
                           <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffdef.vis.cmn.html">att.staffDef.vis.cmn</a></label><span class="classDesc"></span></div>
                           <div class="classContent">
                              <div class="classBox" title="att.staffDef.vis">
                                 <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffdef.vis.html">att.staffDef.vis</a></label><span class="classDesc"></span></div>
                                 <div class="classContent">
                                    <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/staffdef.html">staffDef</a><span class="elementDesc">(staff definition) – Container for staff meta-information.</span></div>
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/scoredef.html">scoreDef</a><span class="elementDesc">(score definition) – Container for score meta-information.</span></div>
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/staffdef.html">staffDef</a><span class="elementDesc">(staff definition) – Container for staff meta-information.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.rehearsal"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.cmn"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Attributes used by scoreDef and staffDef to provide default information about rehearsal
                           numbers/letters.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;attList&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"reh.enclose"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>Describes the enclosing shape for rehearsal marks.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valList <span class="attribute">type=</span><span class="attributevalue">"closed"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"box"</span>&gt;</span>
                                    
                                    <div class="indent6 indent"><span data-indentation="6" class="element">&lt;desc&gt;</span>Enclosed by box.<span data-indentation="6" class="element">&lt;/desc&gt;</span></div>
                                    <span data-indentation="5" class="element">&lt;/valItem&gt;</span></div>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"circle"</span>&gt;</span>
                                    
                                    <div class="indent6 indent"><span data-indentation="6" class="element">&lt;desc&gt;</span>Enclosed by circle.<span data-indentation="6" class="element">&lt;/desc&gt;</span></div>
                                    <span data-indentation="5" class="element">&lt;/valItem&gt;</span></div>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"none"</span>&gt;</span>
                                    
                                    <div class="indent6 indent"><span data-indentation="6" class="element">&lt;desc&gt;</span>No enclosing shape.<span data-indentation="6" class="element">&lt;/desc&gt;</span></div>
                                    <span data-indentation="5" class="element">&lt;/valItem&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valList&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/attDef&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/attList&gt;</span></div>
                        <span data-indentation="1" class="element">&lt;/classSpec&gt;</span></div></code></div>
            </div>
         </div>
      </div><script type="text/javascript">
            
            var tabbedFacets = document.querySelectorAll('.facet ul.tab');
            
            var tabClick = function(e) {
                var style = e.target.getAttribute('data-display');
                var facetId = e.target.parentNode.parentNode.parentNode.parentNode.id;
                setTabs(facetId,style)
            }
            
            for(var facetUl of tabbedFacets) {
                var facetElem = facetUl.parentNode.parentNode;
                var facetId = facetElem.id;
                var storageName = 'meiSpecs_' + facetId + '_display';
                var defaultValue = facetUl.children[0].children[0].getAttribute('data-display');
                
                if(localStorage.getItem(storageName) === null) {
                    setTabs(facetElem.id,defaultValue);
                } else {
                    setTabs(facetElem.id,localStorage.getItem(storageName));
                }
                
                var tabs = facetUl.querySelectorAll('.tab-item a');
                
                for(var tab of tabs) {
                    tab.addEventListener('click',tabClick);
                }
                
            }
            
            function setTabs(facetId,style) {
                
                var storageName = 'meiSpecs_' + facetId + '_display';
                localStorage.setItem(storageName,style);
                
                var facetElem = document.getElementById(facetId);
                
                var oldTab = facetElem.querySelector('.displayTab.active');
                oldTab.classList.remove('active');
                
                var newTab = document.getElementById(facetId + '_' + style + '_tab');
                newTab.classList.add('active');
                
                var oldBox = facetElem.querySelector('.active.facetTabbedContent');
                oldBox.classList.remove('active');
                oldBox.style.display = 'none';
                
                var newBox = document.getElementById(facetId + '_tabbedContent_' + style);
                newBox.classList.add('active');
                newBox.style.display = 'block';
                
            }
        </script></div>
</div>