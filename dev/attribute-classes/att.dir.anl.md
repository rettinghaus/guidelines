---
layout: sidebar
sidebar: s1
version: "dev"
title: "att.dir.anl"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.dir.anl">att.dir.anl</h3>
      <div class="specs">
         <div class="desc">Analytical domain attributes.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.analytical</div>
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
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full"></div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class"></div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module"></div>
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
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="(directive) – An instruction expressed as a combination of text and symbols — such as segno and coda symbols, fermatas over a bar line, etc., typically above, below, or between staves, but not on the staff — that is not encoded elsewhere in more specific elements, like or ."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/dir.html">dir</a></span>, <span class="ident element" title="(dynamic) – Indication of the volume of a note, phrase, or section of music."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/dynam.html">dynam</a></span>, <span class="ident element" title="Text and symbols descriptive of tempo, mood, or style, e.g., &#34;allarg.&#34;, &#34;a tempo&#34;, &#34;cantabile&#34;, &#34;Moderato&#34;, &#34;♩=60&#34;, &#34;Moderato ♩ =60&#34;)."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/tempo.html">tempo</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.dir.anl">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.dir.anl.html">att.dir.anl</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/dir.html">dir</a><span class="elementDesc">(directive) – An instruction expressed as a combination of text and symbols — such
                              as
                              segno and coda symbols, fermatas over a bar line, etc., typically above, below, or
                              between
                              staves, but not on the staff — that is not encoded elsewhere in more specific elements,
                              like
                              <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/tempo.html">tempo</a> or <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/dynam.html">dynam</a>.</span></div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.shared"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/dir.html">dir</a><span class="elementDesc">(directive) – An instruction expressed as a combination of text and symbols — such
                              as
                              segno and coda symbols, fermatas over a bar line, etc., typically above, below, or
                              between
                              staves, but not on the staff — that is not encoded elsewhere in more specific elements,
                              like
                              <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/tempo.html">tempo</a> or <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/dynam.html">dynam</a>.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.dir.anl"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.analytical"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Analytical domain attributes.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
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