---
{"dg-publish":true,"permalink":"/Compendium/Atlas/Plane of Euthymia/Earthen Realm/Earthen Realm/"}
---


![The World - Copy.jpg|banner](/img/user/Assets/Images/Location/The%20World%20-%20Copy.jpg)
###### Earthen Realm
<span class="sub2">:RiGlobalLine: Realm (world)</span>
___

> [!quote|no-t] SUMMARY
> The Earthen Realm or Earth is a modifed version of our present day Earth. Core compositions of minerals, certain aspects of pre-history and various indicators from the modern reality still remain due to [[Sol\|Sol]]'s time-rush when implementing the [[Sol's Reformation Plan\|Reformation Plan]] to prevent humanity from reaching the stars ever again. Magic would keep them complacent and unable to utilize science. 

#### marker
> [!column|flex 3]
> > [!hint]-  NPC's
> > <input type="checkbox" id="npc"/><ul class="sortMenu"><li class="sortIcon">:RiListSettingsLine:<ul class="dropdown npcedit"><li><label for="npc" class="directLabel active">Direct Links Only</label></li><li><label for="npc" class="childLabel">Include Sub-Locations</label></li></ul></li></ul>
> ><pre class="dataview dataview-error">Evaluation Error: SyntaxError: Unexpected token '&gt;&gt;'
    at DataviewInlineApi.eval (plugin:dataview:19027:21)
    at evalInContext (plugin:dataview:19028:7)
    at asyncEvalInContext (plugin:dataview:19038:32)
    at DataviewJSRenderer.render (plugin:dataview:19064:19)
    at DataviewJSRenderer.onload (plugin:dataview:18606:14)
    at DataviewJSRenderer.load (app://obsidian.md/app.js:1:1214378)
    at DataviewApi.executeJs (plugin:dataview:19607:18)
    at DataviewCompiler.eval (plugin:digitalgarden:10760:23)
    at Generator.next (&lt;anonymous&gt;)
    at fulfilled (plugin:digitalgarden:77:24)</pre>
>>```dataviewjs
dv.container.className += ' npcChild';
let page = dv.current().file.path;
let pages = new Set();
let stack = [page];
while (stack.length > 0) {
let elem = stack.pop();
let meta = dv.page(elem);
if (!meta) continue;
for (let inlink of meta.file.inlinks.concat(meta.file.outlinks).array()) {
let locations = dv.page(inlink.path);
if (!locations || pages.has(inlink.path) || inlink.path === meta.locations?.[0]) continue;
 if (dv.array(locations.locations).join(", ").includes(meta.file.path)) {
 pages.add(inlink.path);
 stack.push(inlink.path);
}}}
let data = Array.from(pages)
.filter(p => dv.page(p)?.type === "npc")
.map(p => dv.page(p).headerLink)
.sort((a, b) => {
if (a < b) return -1;
if (a > b) return 1;
return 0;
});
dv.list(data);
> 
>> [!example]- LOCATIONS
- - - Gondwana#Gondwana


- [[Compendium/Atlas/Plane of Euthymia/Earthen Realm/Hanuel/Hanuel#Hanuel\|Hanuel > Hanuel]]
- [[Compendium/Atlas/Plane of Euthymia/Earthen Realm/Hanuel/Hanuel#Hanuel\|Hanuel > Hanuel]]
- - - Pangea#Pangea



{ .block-language-dataview}
>
>> [!note]- HISTORY

{ .block-language-dataview}