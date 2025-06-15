---
{"dg-publish":true,"permalink":"/Compendium/Atlas/Plane of Euthymia/Earthen Realm/Hanuel/Dornfells/Vanyra/Vanyra/","tags":["location/city"]}
---


![[Vanyra.png\|banner]]
###### Vanyra "The City of Opportunity"
<span class="sub2">:FasCity: City</span>
___

> [!quote|no-t] SUMMARY
>An overly tacky city where the [[Compendium/Lore/Organizations/Union\|Union]] operates their Diamond Mining operations.  Founded on said diamond mining operations, many of the members within the city try to dress wealthy to signal their status, even if they are not. It leads to an extremely bizzare state of affairs where the wealthy in Vanyra look poor, and the poor look wealthy. The diamond mines have brought significant business to the area resulting in the average citizen here having a fairly comfortable life. "Poor" in Vanyra is middle-class or upper-middle class practically everywhere else. Crime does run deep within the city despite the average citizen being fairly well off simply due to the sheer indulgence that such wealth brings. The current king of Dornfells, [[King  Irmin\|King  Irmin]] is afraid of overstepping his authority in this region by enforcing many rules upon it or attempting to break up the gangs in this city. Because if he did, would they come for him?

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
const page = dv.current().file.path;
const pages = new Set();
const stack = [page];
while (stack.length > 0) {
const elem = stack.pop();
const meta = dv.page(elem);
if (!meta) continue;
for (const inlink of meta.file.inlinks.concat(meta.file.outlinks).array()) {
const locations = dv.page(inlink.path);
if (!locations || pages.has(inlink.path) || inlink.path === meta.locations?.[0]) continue;
 if (dv.array(locations.locations).join(", ").includes(meta.file.path)) {
 pages.add(inlink.path);
 stack.push(inlink.path);
}}}
const data = Array.from(pages)
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
- [[Compendium/Atlas/Plane of Euthymia/Earthen Realm/Hanuel/Dornfells/Vanyra/Angel's Share/Angel's Share#Angel s Share\|Angel's Share > Angel s Share]]

{ .block-language-dataview}
>
>> [!note]- HISTORY
- \-
- [[Session Notes/Session 07 (2025-04-26)#Session 07\|Session 07 (2025-04-26)]]
- [[Session Notes/Session 06 (2025-03-29)#Session 06\|Session 06 (2025-03-29)]]
- [[Session 05 (2025-03-29)#Session 05\|Session 05 (2025-03-29)]]
- [[Session Notes/Session 04 (2025-03-07)#Session 04\|Session 04 (2025-03-07)]]

{ .block-language-dataview}