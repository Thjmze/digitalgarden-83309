---
{"dg-publish":true,"permalink":"/Compendium/Atlas/Plane of Euthymia/Earthen Realm/Gondwana/Dravinslagg/Dravinslagg/","tags":["location/kingdom","#dravinslaggian"]}
---


![[Dravinslagg.png\|banner]]
###### Dravinslagg
<span class="sub2">:FasChessRook: Kingdom</span>
___

> [!quote|no-t] SUMMARY
>Kingdom is far too generous a way to put this authoritarian backwater. Once it was home to one of the most diverse and innovative communities formed by many different races evolving to cope with the island conditions in different ways. An ambitious man that [[Compendium/Atlas/Plane of Euthymia/Earthen Realm/Gondwana/Dravinslagg/Dravinslaggian\|Dravinslaggian]] history only remembers as "The True Great One" for all records of his name have been expunged (so that unworthy tongues may never utter it again), sought to unite the many islands under one empire. Initially it went great with the Yuan-ti and Hobgoblins uniting under one banner. But the [[Drow\|Drow]] were hesitant to join and instead of accepting that, the "True Great One" forcibly captured their territory with the combined military forces of the Yuan-Ti and Hobgoblins. It was marketed as bring the glory of the newly founded [[Dravinslaggian Empire\|Dravinslaggian Empire]] to the [[soft skin\|soft skins (derogatory)]] who were not built for survival within the harsh conditions of the island. Thus they were conquered and subjugated. This was not without resistance, however. But the fervent supporters of this regime crushed those who rebelled through extremely brutal methods. The one that is most well-remembered due to the [[Compendium/Lore/Organizations/Iron Shadow\|Iron Shadow's]] usage of the technique is skin-flaying. That's all I'll get into. 

#### marker
> [!column|flex 3]
> > [!hint]-  NPC's
> > <input type="checkbox" id="npc"/><ul class="sortMenu"><li class="sortIcon">:RiListSettingsLine:<ul class="dropdown npcedit"><li><label for="npc" class="directLabel active">Direct Links Only</label></li><li><label for="npc" class="childLabel">Include Sub-Locations</label></li></ul></li></ul>
> ><pre class="dataview dataview-error">Evaluation Error: SyntaxError: Unexpected token '&gt;'
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

{ .block-language-dataview}
>> [!note]- HISTORY

{ .block-language-dataview}
#### marker