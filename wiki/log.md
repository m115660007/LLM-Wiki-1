# 知識庫變更與審計日誌 (log.md)

所有對 Wiki 知識網絡的修改（包括資料攝取 ingest、問答沉澱 query-compound、結構健檢 lint）均會在此追加記錄。

---

## [2026-11-17] initialize | 知識庫基礎架構與 agent.md 建立
- **異動檔案**：
  - `agent.md` (新增：維護標準規範與工作流)
  - `wiki/index.md` (新增：總索引導航)
  - `wiki/log.md` (新增：日誌檔案)
  - 建立 `raw/`（獸醫指引、法規、網頁剪藏）與 `wiki/`（禮儀、肢體、互動、情境、性格）目錄結構
- **核心內容摘記**：
  - 完成 Karpathy LLM Wiki 模式落地，確立以 Obsidian 雙向鏈結與 Callout 為主之寫作標準，準備就緒以接收第一批文獻。


## [2026-11-17] ingest | 農業部《寵物飼養與照顧指南－貓篇》
- **來源歸檔**：`raw/regulations/moa-cat-care-guide.md`
- **新增／更新頁面**：
  - `wiki/etiquette/visitor-rules.md` (新增：訪客守則、自主選擇權、禁止手腳當玩具)
  - `wiki/etiquette/cafe-environment-welfare.md` (新增：空間垂直度、紙箱安全處、N+1 貓砂盆)
  - `wiki/body-language/warning-signals.md` (新增：甩尾、飛機耳、瞳孔與三級警戒量表)
  - `wiki/body-language/purring-dual-meaning.md` (新增：呼嚕雙重含意判定流程圖)
  - `wiki/interactions/consent-first-approach.md` (新增：知情同意測試、破冰四步驟)
  - `wiki/interactions/play-rules.md` (新增：獵物三部曲、嚴禁雷射筆、撫摸熱區禁區圖)
  - `wiki/interactions/dangerous-substances.md` (新增：薄荷醇、柑橘柚子帽、蔥蒜巧克力、線狀異物)
  - `wiki/scenarios/multi-cat-conflicts.md` (新增：真打架 vs 玩鬧判別、視線阻斷法)
  - `wiki/scenarios/senior-cats-in-cafe.md` (新增：7歲/11歲老貓照護、動線尊重、幼貓防範)
  - `wiki/index.md` (更新總索引)
- **核心內容摘記**：
  - 成功將第一份官方照顧指引拆解並織入整個 Wiki，奠定貓咖顧客互動規範與行為醫學基礎。


## [2026-11-17] ingest | FelineVMA & iCatCare《Your Cat's Environmental Needs》
- **來源歸檔**：`raw/vet-guidelines/felinevma-icatcare-environmental-needs.md`
- **新增／更新頁面**：
  - `wiki/etiquette/feline-five-pillars.md` (新增：國際貓科醫學會「健康貓咪環境五大支柱」核心理論)
  - `wiki/scenarios/cat-stress-olfactory.md` (新增：嗅覺焦慮、面部費洛蒙磨蹭保護、人造香氛衝擊與 Feliway 應用)
  - `wiki/etiquette/cafe-environment-welfare.md` (更新：納入避難所「雙向進出通道 (Two-way exits)」、單貓尺寸墊高規格)
  - `wiki/interactions/consent-first-approach.md` (更新：強調正向/一致/可預測三大要素，以及 2-7 週幼貓社會化敏感期之影響)
  - `wiki/interactions/play-rules.md` (更新：納入多貓「個別單獨玩耍 (Play Individually)」、益智覓食球 Food Puzzles 與玩具輪換機制)
  - `wiki/index.md` (更新總索引)
- **核心內容摘記**：
  - 引進全球獸醫行為學最權威的「環境五大支柱」框架，大幅提升本知識庫在避難動線、多貓玩耍防爭搶與嗅覺費洛蒙領域的科學深度。


## [2026-11-17] ingest | 農業部《動物展演管理辦法》(113年7月29日修正) 及官方表單
- **來源歸檔**：`raw/regulations/animal-exhibition-regulations-2024.md` 及 6 份官方 DOCX 表單
- **新增／更新頁面**：
  - `wiki/etiquette/legal-exhibition-compliance.md` (新增：合法貓咖法規與顧客責任手冊、展演許可、追逐違法、法定休息權)
  - `wiki/scenarios/scratch-and-bite-first-aid.md` (新增：被貓抓咬傷現場 15 分鐘急救 SOP、巴斯德桿菌與貓抓病警訊)
  - `wiki/etiquette/visitor-rules.md` (更新：將追逐、圍捕貓咪提升為法定禁止行為，增加現場工作人員監管權威)
  - `wiki/etiquette/cafe-environment-welfare.md` (更新：納入法定後場隔離室、雙門防逃設施、急救醫藥箱常備)
  - `wiki/scenarios/senior-cats-in-cafe.md` (更新：補充第 20 條老病弱貓與未離乳幼貓法定免展演保護)
  - `wiki/index.md` (更新總索引)
- **核心內容摘記**：
  - 完整補足台灣法規層面的規範與責任義務，確立貓咖訪客不僅是顧客，更是負有動保法定自律義務的參訪者。


## [2026-11-17] ingest | 貓咖 MOCHA 台北信義店營運店規與店貓品種名單
- **來源歸檔**：`raw/web-clippings/cat-mocha-taipei-xinyi.md`
- **新增／更新頁面**：
  - `wiki/personalities/popular-cat-breeds-guide.md` (新增：常見貓咖品種特質、摺耳貓軟骨痛點、曼赤肯短腿脊椎負擔、英短討厭被抱)
  - `wiki/scenarios/visiting-with-kids.md` (新增：4~12歲兒童同行家長指引、監護責任、紅綠燈守則、一指神功)
  - `wiki/interactions/photography-etiquette.md` (新增：手機拍照禮節、強制關閉閃光燈之視網膜保護原理、長焦 2x/3x 構圖技巧)
  - `wiki/etiquette/visitor-rules.md` (更新：補充拍照禮儀與兒童同行規範之超連結)
  - `wiki/index.md` (更新總索引)
- **核心內容摘記**：
  - 首度開闢 `wiki/personalities/` 分類，結合知名連鎖貓咖品種名單，建立品種遺傳病學照護指引與親子攝影實務手冊。


## [2026-11-17] ingest | 紅玥緬因貓咖啡藝廊營運店規與訂位須知
- **來源歸檔**：`raw/web-clippings/red-moon-maine-coon-cafe.md`
- **新增／更新頁面**：
  - `wiki/interactions/treat-and-churu-feeding.md` (新增：肉泥與零食安全餵食指南、小湯匙安全法、防吞塑膠袋腸梗阻、防搶食圍攻)
  - `wiki/scenarios/dining-with-cats-table-manners.md` (新增：貓咖餐飲防護與桌面防貓禮節、熱飲防燙、嚴禁用餐具逗貓、落毛免責)
  - `wiki/etiquette/hygiene-and-shoe-protocol.md` (新增：入店衛生防線、脫鞋更換室內拖、洗手乳 20 秒抗貓瘟動線、隨身物品防護)
  - `wiki/personalities/popular-cat-breeds-guide.md` (更新：新增緬因貓專題特寫、巨大體型手勁與席地平視互動守則)
  - `wiki/etiquette/visitor-rules.md` (更新：串聯衛生動線、桌面禮節與肉泥餵食指南)
  - `wiki/index.md` (更新總索引)
- **核心內容摘記**：
  - 補足貓咖「餐飲與動物共處」高難度場景下的防護規範，以及新手餵食高誘惑肉泥時的防咬、防吞異物與防圍攻之關鍵 SOP。


## [2026-11-17] compound-slides | 建立《新手貓咪互動教學》HTML 投影簡報
- **產出檔案**：
  - `slides/index.html` (獨立可離線瀏覽的現代化互動投影片)
- **結合視覺素材**：
  - 全面導入 `assets/` 內的賓士店長貓貼紙插圖（涵蓋正坐、飛機耳大瞳孔警戒、翻白肚放鬆、瞇瞇眼睡眠、玩耍仰臥等完整表情肢體）
- **投影片 10 大主題**：
  1. 封面：讀懂貓訊號・安心好相處（店長端坐迎接）
  2. 核心哲學：把主控權徹底還給貓（AAFP Pillar 4 與動保法定防線）
  3. 入店三道防線：換鞋防貓瘟、洗手 20 秒、嚴禁薄荷腦柑橘
  4. 破冰四步驟：知情同意測試 (Consent Test) 與一指神功
  5. 撫摸地圖：下巴耳後熱區 vs 翻肚/肉球/尾巴禁區（破除翻肚迷思）
  6. 讀懂微表情：尾巴拍地、飛機耳瞳孔放大預警與呼嚕雙重含意
  7. 逗貓玩耍：獵物三部曲、實體捕獲、嚴禁手指逗咬與雷射筆
  8. 肉泥餵食與桌面防護：小湯匙餵食法防吞異物、熱飲置中防燙傷
  9. 特殊品種與兒童安全：摺耳貓軟骨痛點、曼赤肯短腿、兒童三不原則
  10. 意外應變與守護約定：抓咬傷 15 分鐘流動水沖洗急救與人貓共好公約
