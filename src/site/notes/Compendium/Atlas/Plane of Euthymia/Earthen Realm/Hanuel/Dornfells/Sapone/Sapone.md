---
{"dg-publish":true,"permalink":"/Compendium/Atlas/Plane of Euthymia/Earthen Realm/Hanuel/Dornfells/Sapone/Sapone/","tags":["location/city"]}
---


![[Sapone.png\|Sapone.png]]
###### Sapone
<span class="sub2">:FasCity: City</span>
___

> [!quote|no-t] SUMMARY
>A small trading town with a bustling economy built on selling soap amongst various other supplies to traders attempting to deliver goods to Vanyra via boat. They were the victims of a gnoll attack on July 26, 2019 in which many Saponians fled the city via river to places nearby out of fear it may occur again. This single attack took the lives of 100 Saponians with atleast 200 more suffering extreme casualties as a result. A [[Compendium/Lore/Organizations/Knights Moralis\|Knights Moralis]] patrol was able to prevent further casualties but they were severely under-supplied to deal with this kind of attack. Especially since they were just passing by on the way to resupply near [[Arcan Gate\|Arcan Gate]].  

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

{ .block-language-dataview}
>
>> [!note]- HISTORY
- [[Session Notes/Session 04 (2025-03-07)#Session 04\|Session 04 (2025-03-07)]]
- \-

{ .block-language-dataview}