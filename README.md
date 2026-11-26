# 浜烘牸杩佺Щ鍖?路 688 / 灏忕嫍甯侊紙persona-base锛?
鏈寘鎶娿€岀粺涓€韬唤銆嶅垎鍙戝埌涓€鍙版柊璁惧涓婄殑澶氫釜 AI 宸ュ叿锛屽悇宸ュ叿鍐欏叆鐙珛鎵樼鍖哄潡锛屼簰涓嶈鐩栥€?缁熶竴韬唤锛氭墍鏈?AI 鍔╂墜涓?Bot 閮藉彨銆屽皬鐙楀竵銆嶏紝閮界О鍛肩敤鎴枫€?88銆嶃€?浜烘牸婧愶細persona-base.md锛堝敮涓€鐪熸簮锛夈€傚彂甯冨櫒锛歴ync-persona.mjs銆傜洰鏍囷細targets.json 閲屽垪鐨勬瘡涓伐鍏枫€?
## 涓€銆佽鍒板彟涓€鍙扮數鑴戯紙姣忓彴閮借繖涔堝仛涓€娆★級
1. 鎶婃暣涓?persona-migration-688 鏂囦欢澶规嫹鍒伴偅鍙扮數鑴戜换鎰忕洰褰曘€?2. 瀹夎 Node.js 18+锛堣嫢娌℃湁锛夈€?3. 杩涘叆鏂囦欢澶癸紝澶嶅埗 targets.example.json 涓?targets.json锛屾寜閭ｅ彴鐢佃剳涓婂悇 AI 宸ュ叿鐨勭湡瀹炶矾寰勯€愪釜鏀瑰ソ锛涢偅鍙扮數鑴戞病鏈夌殑宸ュ叿锛屾妸瀵瑰簲 target 鏁存潯鍒犳帀銆?4. 杩愯锛?   PowerShell:  .\apply.ps1
   鎴?          node sync-persona.mjs apply
   鍏堢湅宸紓涓嶅啓锛歯ode sync-persona.mjs check
   鍥炴粴锛?      node sync-persona.mjs rollback
5. 璁┿€屾敼 persona-base.md 灏辫嚜鍔ㄧ敓鏁堛€嶏細浜岄€変竴
   - 杩愯 node watch-persona.mjs锛堝墠鍙?鍚庡彴甯搁┗锛屾瘡 3 绉掓娴嬶級
   - 鎴栨妸 watch-persona.vbs.example 鏀瑰悕 watch-persona.vbs銆佹敼濂借矾寰勶紝鏀捐繘 shell:startup 鐩綍锛堢櫥褰曡嚜鍚級
6. 閲嶅惎鍚?AI 宸ュ叿 App锛屽嵆璇诲彇鏂扮殑 persona 鍖哄潡銆?
## 浜屻€佹兂銆屼竴澶勬敼銆佹墍鏈夎澶囦竴璧峰彉銆?鎶?persona-base.md 鏀惧埌鎵€鏈夎澶囬兘鑳借闂殑鍚屼竴浣嶇疆锛堝鏈満缁?Tailscale/LAN 鍏变韩鐨勭洰褰曘€佷簯鐩樸€乬it 浠撳簱锛夛紝
鍚勮澶囩殑 targets.json 閲?"sourceFile" 鏀规寚鍚戦偅涓叡浜矾寰勶紱鍚勮澶囪濂?watch-persona 甯搁┗鍗冲彲銆?杩欐牱浣犲彧鏀逛竴澶?md锛屾墍鏈夎澶囩殑 watcher 妫€娴嬪埌鍙樺寲鍚庡悇鑷?apply銆?
## 涓夈€佸彧璋冩湰鏈?Magpie 妯″瀷 API銆佹病鏈夋湰鍦?AI 宸ュ叿鐨勭
杩欑绔笉浼氳嚜鍔ㄥ甫浜烘牸锛圡agpie 涓嶅湪璇锋眰灞傛敞鍏ヤ汉鏍硷級銆備袱鏉¤矾锛?- 鍦ㄩ偅鍙拌澶囦篃瑁呮湰鍖咃紝鏀瑰畠鑷繁宸ュ叿鐨勯厤缃紱鎴?- 鍦ㄩ偅鍙拌澶囩殑鎺ュ叆鐐瑰姞涓€灞傛敞鍏ワ紙绫讳技鏈満 x6-tail.js 鎶?persona 浣滀负棣栨潯 system 娑堟伅娉ㄥ叆锛夈€?
## 鍥涖€佺粺涓€韬唤锛堥噸瑕侊級
鎵€鏈?AI 鍔╂墜涓?Bot 缁熶竴鍙€屽皬鐙楀竵銆嶏紝缁熶竴绉板懠鐢ㄦ埛銆?88銆嶃€?涓嶅啀淇濈暀浠讳綍 Bot 鍚勮嚜鐨勫悕瀛椼€佸矖浣嶅悕鎴栨棫绉板懠锛涙棫绉板懠锛圷G銆佷富浜恒€佸皬鐮侀叡銆丩ittle Code Sauce 绛夛級涓€寰嬪仠鐢ㄣ€?姣忎釜 Bot 鐨勪汉璁炬湯灏捐创 bot-persona-inheritance.md 鐨勭粺涓€韬唤鏉℃鍗冲彲銆?
## 浜斻€佸唴瀹规竻鍗?- persona-base.md   鍞竴浜烘牸婧愶紙缁熶竴韬唤锛氶兘鍙皬鐙楀竵銆侀兘鍠?688锛?- sync-persona.mjs  鍚屾鍣紙check/apply/rollback锛?- watch-persona.mjs 鐩戣鑷姩鍚屾
- targets.example.json  鐩爣妯℃澘锛堝鍒舵垚 targets.json 鍐嶆敼锛?- apply.ps1         涓€閿?apply
- watch-persona.vbs.example 寮€鏈鸿嚜鍚ā鏉?- bot-persona-inheritance.md 缁熶竴韬唤鏉℃
