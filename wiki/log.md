# 知識庫演進日誌 (Evolution Log)

本檔案為 append-only 格式，記錄知識庫自建立以來的每一次 Ingest、Lint 與結構更新。

---

## [2026-11-11] system | 建立專案骨幹與 AGENTS.md 運作規範
- 定義專案核心為「職能治療團體活動資料庫」。
- 鎖定四大族群（兒童、精神科病房、社區精神復健、高齡長照）。
- 導入 Karpathy LLM Wiki 三層架構（Raw Sources -> Markdown Wiki -> Web UI）。
- 確立沈星回（Xavier）星河紫暖色調 UI 規範。

## [2026-11-11] ingest | 兒童職能活動：星際黏土探險 (sensory-clay-planet)
- 來源：`sources/clinical-notes-2026.md` 隨筆一
- 新增活動：`wiki/activities/sensory-clay-planet.md`
- 關聯更新：`wiki/populations/pediatrics.md`、`wiki/skills/fine-motor.md`、`wiki/skills/sensory-regulation.md`

## [2026-11-11] ingest | 精神科病房活動：星空剪貼心世界 (expressive-emotion-collage)
- 來源：`sources/clinical-notes-2026.md` 隨筆二
- 新增活動：`wiki/activities/expressive-emotion-collage.md`
- 關聯更新：`wiki/populations/psychiatric-inpatient.md`、`wiki/skills/social-interaction.md`、`wiki/skills/fine-motor.md`

## [2026-11-11] ingest | 社區精神復健活動：星光烘焙工坊 (community-baking-workshop)
- 來源：`sources/clinical-notes-2026.md` 隨筆三
- 新增活動：`wiki/activities/community-baking-workshop.md`
- 關聯更新：`wiki/populations/community-psychiatry.md`、`wiki/skills/executive-function.md`、`wiki/skills/social-interaction.md`

## [2026-11-11] ingest | 高齡長照活動：暖心星光懷舊氣球球賽 (reminiscence-starlight-ball)
- 來源：`sources/clinical-notes-2026.md` 隨筆四
- 新增活動：`wiki/activities/reminiscence-starlight-ball.md`
- 關聯更新：`wiki/populations/geriatric-care.md`、`wiki/skills/sensory-regulation.md`、`wiki/skills/social-interaction.md`


## [2026-11-11] batch-ingest | 批量收錄 sources/ 22 份臨床計畫書

## [2026-11-11] ingest | 彩球挑戰大冒險與紙杯花藝創作 (ped-wk1-color-ball-flower)
- 適用族群：兒童職能 ($(@{id=ped-wk1-color-ball-flower; title=彩球挑戰大冒險與紙杯花藝創作; population=pediatrics; population_name=兒童職能; duration=55分鐘; group_size=6-8人; skills=System.Object[]; materials=System.Object[]; substitute_materials=巧拼可用地墊替代，彩球可用報紙揉球貼彩色膠帶替代，紙箱可直接以不同色紙標記。; rationale=結合大動作動態平衡遊戲與精細紙杯花藝手作，提供多元動作刺激，藉由獎勵制度建立規則感與同儕互助精神。; goals=System.Object[]; space_setup=前半部為平衡木與過河石運送障礙動線，後半部為小組手作矮桌。; process=System.Object[]; grading_down=走平衡木時由協同老師牽單手走；紙杯杯壁由老師預先剪好一半，讓學員剪最後1公分。; grading_up=增加過河石間距並要求單腳站立停格2秒；紙杯花瓣增加雙層重疊與葉片剪貼細節。; safety=安全剪刀嚴格規範不對人；走平衡木兩側需有防護，防止推擠跌倒。; tags=System.Object[]}.population))
- 主要介入能力：精細動作與手部協調、社交互動與團體合作
- 建立檔案：wiki/activities/ped-wk1-color-ball-flower.md`n
## [2026-11-11] ingest | 九宮格丟沙包與彩紙撕貼畫 (ped-wk2-sandbag-collage)
- 適用族群：兒童職能 ($(@{id=ped-wk2-sandbag-collage; title=九宮格丟沙包與彩紙撕貼畫; population=pediatrics; population_name=兒童職能; duration=55分鐘; group_size=6-8人; skills=System.Object[]; materials=System.Object[]; substitute_materials=沙包可用厚襪子包裹米粒或紅豆自製；底稿可用簡報投影手繪描圖。; rationale=透過九宮格目標投擲訓練上肢力量調控與手眼協調，並以撕貼畫訓練指尖捏抓力量與觸覺專注，增進情緒安定。; goals=System.Object[]; space_setup=地面張貼兩組九宮格與50cm/70cm投擲線，教室角落設巧拼冷靜區。; process=System.Object[]; grading_down=投擲距離縮短至30cm且只分近遠兩格；撕紙改為由老師撕成長條，孩童再撕小塊。; grading_up=投擲線退至1公尺且指定特定數字組合；拼貼圖案要求顏色漸層過渡。; safety=沙包嚴禁朝他人身體投擲；活動過程不得超越投擲線與推擠。; tags=System.Object[]}.population))
- 主要介入能力：精細動作與手部協調、感覺處理與情緒調節
- 建立檔案：wiki/activities/ped-wk2-sandbag-collage.md`n
## [2026-11-11] ingest | 呼啦圈穿梭、足球射門與輕黏土動物捏塑 (ped-wk3-soccer-clay)
- 適用族群：兒童職能 ($(@{id=ped-wk3-soccer-clay; title=呼啦圈穿梭、足球射門與輕黏土動物捏塑; population=pediatrics; population_name=兒童職能; duration=55分鐘; group_size=6-8人; skills=System.Object[]; materials=System.Object[]; substitute_materials=球門可用小矮凳代替；呼啦圈可用粗繩圍成圓圈代替。; rationale=手牽手傳遞呼啦圈能建立緊密同儕信任，足球射門促進下肢單腳站立平衡，黏土造型則鍛鍊雙手精細分工捏塑。; goals=System.Object[]; space_setup=空曠動線規劃雪花片球門射門區，後方配置黏土操作桌椅。; process=System.Object[]; grading_down=踢球球門寬度加倍，距離縮短至1公尺；黏土由老師協助分等份搓圓，孩童負責壓扁貼上。; grading_up=射門前需先踩過波浪板再起腳；黏土需自行混色並做出細微章魚觸手紋路。; safety=踢球嚴禁推擠同伴與大力亂踢；黏土嚴禁放入口中，操作完畢徹底洗手。; tags=System.Object[]}.population))
- 主要介入能力：精細動作與手部協調、社交互動與團體合作
- 建立檔案：wiki/activities/ped-wk3-soccer-clay.md`n
## [2026-11-11] ingest | 角錐障礙足球賽與旋轉紙杯風車手作 (ped-wk4-obstacle-pinwheel)
- 適用族群：兒童職能 ($(@{id=ped-wk4-obstacle-pinwheel; title=角錐障礙足球賽與旋轉紙杯風車手作; population=pediatrics; population_name=兒童職能; duration=55分鐘; group_size=6-8人; skills=System.Object[]; materials=System.Object[]; substitute_materials=角錐可用裝水寶特瓶替代；保麗龍膠可用雙面膠加白膠替代。; rationale=將大動作S型繞錐運球與細緻口腔吹氣風車結合，全面整合兒童之動作計畫、手指工具操作與口腔肌群。; goals=System.Object[]; space_setup=設置S型角錐障礙動線與球門，旁邊長桌配置風車手作工具材料。; process=System.Object[]; grading_down=風車軸心與小洞由老師預先鑽好；踢球障礙物間距加大。; grading_up=風車雙層扇葉對稱彩繪；運球限制左右腳輪流觸球前進。; safety=安全剪刀不拿來揮舞；吹風車時提醒調節呼吸，避免過度用力頭暈。; tags=System.Object[]}.population))
- 主要介入能力：精細動作與手部協調、執行功能與認知規劃
- 建立檔案：wiki/activities/ped-wk4-obstacle-pinwheel.md`n
## [2026-11-11] ingest | 拯救食物大作戰 — 兒童感覺動作與蔬果認知冒險 (ped-rescue-food-adventure)
- 適用族群：兒童職能 ($(@{id=ped-rescue-food-adventure; title=拯救食物大作戰 — 兒童感覺動作與蔬果認知冒險; population=pediatrics; population_name=兒童職能; duration=60分鐘; group_size=4-6人; skills=System.Object[]; materials=System.Object[]; substitute_materials=瓢蟲墊可用長條觸覺平衡板或枕頭排列代替；蔬果拼圖可用自製彩色圖卡剪開代替。; rationale=透過「奪回小動物被怪獸搶走的食物」故事包裝，讓孩童在平衡過橋動線中訓練姿勢控制、視覺搜尋與口語命名能力。; goals=System.Object[]; space_setup=圓桌（怪獸取卡區）→ 長瓢蟲墊（獨木橋）→ 方桌（小動物的家拼圖區），單向闖關循環動線。; process=System.Object[]; grading_down=瓢蟲墊旁由老師牽手走；拼圖卡片提供2選1降低視覺搜尋難度。; grading_up=拼圖卡片改為反面朝上需盲抽翻面配對；要求講出該蔬果的特徵（如口感、生長在哪裡）。; safety=長瓢蟲墊兩側全程安排帶領者守護防止跌落；卡牌防撕防刮手。; tags=System.Object[]}.population))
- 主要介入能力：精細動作與手部協調、執行功能與認知規劃
- 建立檔案：wiki/activities/ped-rescue-food-adventure.md`n
## [2026-11-11] ingest | 撿到一塊錢與存錢大作戰 — 注意力與動作協調團體 (ped-saving-money-detective)
- 適用族群：兒童職能 ($(@{id=ped-saving-money-detective; title=撿到一塊錢與存錢大作戰 — 注意力與動作協調團體; population=pediatrics; population_name=兒童職能; duration=60分鐘; group_size=4-6人; skills=System.Object[]; materials=System.Object[]; substitute_materials=平衡木可用彩色地膠貼直線代替；存錢筒可用打洞紙盒代替。; rationale=藉由品德繪本引發動機，在運送硬幣走平衡木的過程中鍛鍊手眼協調、工具持握穩定與分類認知能力。; goals=System.Object[]; space_setup=圓桌（線索小偷卡區）→ 平衡木（走道路線）→ 方桌警察局（分類存錢筒）→ 巧拼跳格（回程路線）。; process=System.Object[]; grading_down=運硬幣換用大凹槽湯匙或徒手抓握硬幣；平衡木高度降至地面。; grading_up=改用平底小塑膠湯匙運送50元硬幣；增加特徵卡為4重複合條件（顏色、角、斑點、尾巴）。; safety=硬幣與小配件全程嚴密看管，嚴防口慾期幼童誤吞；平衡木旁舖設軟墊。; tags=System.Object[]}.population))
- 主要介入能力：執行功能與認知規劃、精細動作與手部協調
- 建立檔案：wiki/activities/ped-saving-money-detective.md`n
## [2026-11-11] ingest | 生活問答練功坊 — 語言表達與敏感社交問題應對 (psych-ward-social-qa)
- 適用族群：精神科病房 ($(@{id=psych-ward-social-qa; title=生活問答練功坊 — 語言表達與敏感社交問題應對; population=psychiatric-inpatient; population_name=精神科病房; duration=60分鐘; group_size=8-12人; skills=System.Object[]; materials=System.Object[]; substitute_materials=無投影機時改以手寫大字卡或列印題目紙傳閱。; rationale=病房個案重返家庭時常面臨親友過度關切或敏感詢問。透過三段式音樂傳球遊戲，由淺入深練習口語組織、句子重組與得體的人際界線應對。; goals=System.Object[]; space_setup=排列U型長桌，保留中央走道便於傳球，前方投影螢幕清晰無遮擋。; process=System.Object[]; grading_down=提供固定兩句話術模板（如『謝謝關心，目前以調養身體為主』）讓個案照著唸。; grading_up=由帶領者現場即興模擬尖銳長輩提問，學員需自主靈活組織兼具禮貌與防禦的成熟回答。; safety=活動討論嚴格保護個案隱私，不強迫揭露個人真實病史；嚴禁同儕互相探人隱私或訕笑。; tags=System.Object[]}.population))
- 主要介入能力：社交互動與團體合作、執行功能與認知規劃
- 建立檔案：wiki/activities/psych-ward-social-qa.md`n
## [2026-11-11] ingest | 元宵紙燈籠製作 — 手部精細動作與節慶認知團體 (psych-ward-lantern-origami)
- 適用族群：精神科病房 ($(@{id=psych-ward-lantern-origami; title=元宵紙燈籠製作 — 手部精細動作與節慶認知團體; population=psychiatric-inpatient; population_name=精神科病房; duration=60分鐘; group_size=8-12人; skills=System.Object[]; materials=System.Object[]; substitute_materials=色紙可用乾淨廣告傳單裁切方塊替代；底稿紙可用牛皮紙替代。; rationale=結合元宵民俗節日，透過步驟分級摺紙強化手指靈巧度、指尖捏力與順序記憶力，營造節慶希望感。; goals=System.Object[]; space_setup=四人一桌分組配置，每桌配發材料盒；前方白板張貼大圖解折紙步驟範本。; process=System.Object[]; grading_down=提供已折出米字底痕的半成品色紙，或改做只需兩次對折的平面燈籠。; grading_up=挑戰立體多面體折紙燈籠，並要求在燈籠四面手寫燈謎籤詩。; safety=剪刀嚴格編號清點收繳；色紙紙緣防刮手；躁動學員給予即時關懷。; tags=System.Object[]}.population))
- 主要介入能力：精細動作與手部協調、執行功能與認知規劃
- 建立檔案：wiki/activities/psych-ward-lantern-origami.md`n
## [2026-11-11] ingest | 日常生活猜燈謎 — 記憶活化與生活常識益智團體 (psych-ward-riddle-quiz)
- 適用族群：精神科病房 ($(@{id=psych-ward-riddle-quiz; title=日常生活猜燈謎 — 記憶活化與生活常識益智團體; population=psychiatric-inpatient; population_name=精神科病房; duration=60分鐘; group_size=10-15人; skills=System.Object[]; materials=System.Object[]; substitute_materials=若無投影設備，改用手寫大字卡掛在白板上展示題目。; rationale=藉由日常生活用品（牙刷、洗衣機、悠遊卡、提款機）與節慶猜謎，刺激語意長期記憶、特徵歸納能力與現實導向生活自理認知。; goals=System.Object[]; space_setup=分四組長桌配置，中央走道空出，投影螢幕正對全體座位，白板計分榜分明。; process=System.Object[]; grading_down=提供二選一或三選一提示卡片；允許同桌組員合力補充回答。; grading_up=限制形容詞必須在3~5字內精簡完成，訓練語意概括與口語衝動抑制能力。; safety=引導友善良性競爭，適時平衡各組得分，避免學員產生挫折或敵對情緒。; tags=System.Object[]}.population))
- 主要介入能力：執行功能與認知規劃、社交互動與團體合作
- 建立檔案：wiki/activities/psych-ward-riddle-quiz.md`n
## [2026-11-11] ingest | 櫻花盛開 — 手部精細摺紙與春季感官藝術團體 (psych-ward-cherry-blossom)
- 適用族群：精神科病房 ($(@{id=psych-ward-cherry-blossom; title=櫻花盛開 — 手部精細摺紙與春季感官藝術團體; population=psychiatric-inpatient; population_name=精神科病房; duration=80分鐘; group_size=8-12人; skills=System.Object[]; materials=System.Object[]; substitute_materials=若無彩色底稿紙，可用厚卡紙或牛皮紙手繪深色樹枝背景。; rationale=藉由春暖花開的自然美景喚醒生命感知，透過多步驟對稱折疊與剪紙櫻花，改善手眼協調與步驟記憶，舒緩住院焦慮。; goals=System.Object[]; space_setup=A教室長桌配置，前方大螢幕播放各類櫻花美景與分解折紙短片。; process=System.Object[]; grading_down=提供已劃出剪裁紅虛線的紙胚；允許只製作步驟較少的剪紙版櫻花。; grading_up=挑戰五瓣立體心形花瓣互鎖組裝，並手繪精緻櫻花樹枝幹遠近光影。; safety=剪刀清點收納列管；注意學員手部施力避免痙攣或過度疲乏。; tags=System.Object[]}.population))
- 主要介入能力：精細動作與手部協調、感覺處理與情緒調節
- 建立檔案：wiki/activities/psych-ward-cherry-blossom.md`n
## [2026-11-11] ingest | 澄清湖棒球回憶 — 球衣摺紙與在地生活連結團體 (psych-ward-baseball-origami)
- 適用族群：精神科病房 ($(@{id=psych-ward-baseball-origami; title=澄清湖棒球回憶 — 球衣摺紙與在地生活連結團體; population=psychiatric-inpatient; population_name=精神科病房; duration=80分鐘; group_size=8-12人; skills=System.Object[]; materials=System.Object[]; substitute_materials=球場底稿可直接在綠色卡紙上用白筆劃出內外野菱形線條。; rationale=結合高雄在地澄清湖棒球場地緣記憶與經典運動回憶，透過球衣、球帽摺紙與手繪縫線，提升專注力、生活參與熱情與精細手功能。; goals=System.Object[]; space_setup=長桌配置，前方投影澄清湖球場照片與球員球衣特寫範本。; process=System.Object[]; grading_down=球帽改為平面梯形折法；球衣由帶領者協助領口對齊翻折。; grading_up=自行繪製特定職棒球隊隊徽，並手繪看台觀眾席與球場看板豐富畫面。; safety=剪刀清點管制；維持討論氣氛專注於運動精神，避免激動球隊口角爭執。; tags=System.Object[]}.population))
- 主要介入能力：精細動作與手部協調、執行功能與認知規劃
- 建立檔案：wiki/activities/psych-ward-baseball-origami.md`n
## [2026-11-11] ingest | 手功能活動-幸運草 — 靈巧度訓練與祝福手作 (psych-ward-clover-handcraft)
- 適用族群：精神科病房 ($(@{id=psych-ward-clover-handcraft; title=手功能活動-幸運草 — 靈巧度訓練與祝福手作; population=psychiatric-inpatient; population_name=精神科病房; duration=75分鐘; group_size=8-12人; skills=System.Object[]; materials=System.Object[]; substitute_materials=若無雙面色紙可用單面色紙反折展示白邊；捲莖筷子可用原子筆桿替代。; rationale=藉由四葉幸運草寓意帶來希望與愛。結合四角向心翻摺愛心葉片、斜捲圓筒紙莖與立體蝴蝶，全面訓練手指兩側指力與視覺空間翻轉。; goals=System.Object[]; space_setup=10K交誼廳長桌配置，每桌配備材料杯與口紅膠，前方展示步驟放大模型。; process=System.Object[]; grading_down=葉片折疊由老師預先標出折線；莖部若難捲可直接手繪或提供現成紙條貼上。; grading_up=將葉片擴增為五葉草（代表財富），並在蝴蝶翅膀剪出精緻鏤空圖案。; safety=筷子等細長工具需完整登記回收；隨時關注學員有無挫折反應適時協助。; tags=System.Object[]}.population))
- 主要介入能力：精細動作與手部協調、感覺處理與情緒調節
- 建立檔案：wiki/activities/psych-ward-clover-handcraft.md`n
## [2026-11-11] ingest | 手功能活動-螢火蟲 — 注意力與指尖肌力訓練團體 (psych-ward-firefly-origami)
- 適用族群：精神科病房 ($(@{id=psych-ward-firefly-origami; title=手功能活動-螢火蟲 — 注意力與指尖肌力訓練團體; population=psychiatric-inpatient; population_name=精神科病房; duration=75分鐘; group_size=8-10人; skills=System.Object[]; materials=System.Object[]; substitute_materials=發光貼紙可用黃色彩筆或螢光筆直接點畫替代；底紙可用黑色卡紙呈現夜空。; rationale=螢火蟲在微弱環境中發光，象徵黑暗中的希望。透過16格精密棋盤折痕與水邊小草折疊，訓練持續性注意力與精細指尖捏壓功能。; goals=System.Object[]; space_setup=10K交誼廳桌椅排列，每人提供軟墊板方便折紙施力，前置大張示範圖解。; process=System.Object[]; grading_down=色紙預先用壓線筆劃出16格線條輔助折疊；螢火蟲隻數減少為1-2隻。; grading_up=在夜景底紙上手繪透明玻璃罐，將螢火蟲巧妙安排在罐內與罐外飛舞光軌中。; safety=工具材料確實收繳清點；陪伴因手抖或肌力不足折不準之個案，肯定其參與努力。; tags=System.Object[]}.population))
- 主要介入能力：精細動作與手部協調、執行功能與認知規劃
- 建立檔案：wiki/activities/psych-ward-firefly-origami.md`n
## [2026-11-11] ingest | 「營」在起跑點 — 均衡飲食認知與健康餐盤手作 (comm-psych-nutrition-plate)
- 適用族群：社區精神復健 ($(@{id=comm-psych-nutrition-plate; title=「營」在起跑點 — 均衡飲食認知與健康餐盤手作; population=community-psychiatry; population_name=社區精神復健; duration=80分鐘; group_size=10-15人; skills=System.Object[]; materials=System.Object[]; substitute_materials=食材剪貼若無學習單，可直接從超商宣傳DM中剪取實物照片拼貼。; rationale=精神復健學員常因獨居或藥物影響有代謝症候群困擾。透過「食物紅綠燈」與自製均衡餐盤，強化健康飲食IADL自我管理能力。; goals=System.Object[]; space_setup=日間病房A教室課桌椅排列，前方投影影片，中後方保留小組討論與剪貼空間。; process=System.Object[]; grading_down=餐盤學習單提供預先分類框格，學員只需將已剪好食物貼在正確格位。; grading_up=計算該餐盤之大略預算金額與膳食纖維熱量分配，符合真實外食採買規劃。; safety=剪刀清點防範；鼓勵健康飲食但避免評判學員身材引發自卑焦慮。; tags=System.Object[]}.population))
- 主要介入能力：執行功能與認知規劃、社交互動與團體合作
- 建立檔案：wiki/activities/comm-psych-nutrition-plate.md`n
## [2026-11-11] ingest | 應變達人九是你 — 地板九宮格與生活情境危機應變 (comm-psych-situational-bingo)
- 適用族群：社區精神復健 ($(@{id=comm-psych-situational-bingo; title=應變達人九是你 — 地板九宮格與生活情境危機應變; population=community-psychiatry; population_name=社區精神復健; duration=60分鐘; group_size=8-12人; skills=System.Object[]; materials=System.Object[]; substitute_materials=九宮格可用巧拼地墊拼成；情境題目可依學員平時遭遇動態擴增手寫題卡。; rationale=社區學員獨立外出時常面臨突發問題（搭錯車、ATM卡住、看診預約）。藉由趣味丟球闖關，模擬生活危機並演練解決步驟。; goals=System.Object[]; space_setup=呈泰日間機構活動大廳，地板黏貼大九宮格，設置投擲線與圍坐觀眾席。; process=System.Object[]; grading_down=投中後若一時想不出來，由小組夥伴提供2個提示選項二選一。; grading_up=增加複合多重突發條件（例如身上只有悠遊卡且餘額不足，迷路時如何向路人求助）。; safety=地板紙球防踩踏滑倒；回答過程秉持正向支持，絕不嘲笑任何回答方式。; tags=System.Object[]}.population))
- 主要介入能力：執行功能與認知規劃、社交互動與團體合作
- 建立檔案：wiki/activities/comm-psych-situational-bingo.md`n
## [2026-11-11] ingest | 聖誕「星」願滿天飛 — 立體剪紙與空間美化合作團體 (comm-psych-christmas-star)
- 適用族群：社區精神復健 ($(@{id=comm-psych-christmas-star; title=聖誕「星」願滿天飛 — 立體剪紙與空間美化合作團體; population=community-psychiatry; population_name=社區精神復健; duration=75分鐘; group_size=10-15人; skills=System.Object[]; materials=System.Object[]; substitute_materials=裝飾紙材可用舊樂譜或彩色雜誌廣告頁替代，營造現代復古拼貼感。; rationale=藉由合力完成機構四樓教室、樓梯牆壁與公佈欄之聖誕節慶佈置，培養學員團隊分工、工具共享協商與環境歸屬感。; goals=System.Object[]; space_setup=呈泰日間機構大教室，區分高功能組（立體星星與雪花）與低功能組（平面薑餅人與拐杖糖），設立牆面張貼動線。; process=System.Object[]; grading_down=低功能學員提供厚紙剪裁安全版型，著重於塗膠、黏貼棉花球與裝飾彩繪。; grading_up=高功能學員擔任組長，自主度量對角線折疊大尺寸立體星芒並規劃整體空間動線。; safety=張貼高處作品嚴禁站在活動椅子上，必須由工作人員使用安全梯或長柄工具協助。; tags=System.Object[]}.population))
- 主要介入能力：社交互動與團體合作、精細動作與手部協調
- 建立檔案：wiki/activities/comm-psych-christmas-star.md`n
## [2026-11-11] ingest | 撕在有藝思 — 壓力宣洩與撕紙藝術創作團體 (comm-psych-tear-art-therapy)
- 適用族群：社區精神復健 ($(@{id=comm-psych-tear-art-therapy; title=撕在有藝思 — 壓力宣洩與撕紙藝術創作團體; population=community-psychiatry; population_name=社區精神復健; duration=75分鐘; group_size=8-12人; skills=System.Object[]; materials=System.Object[]; substitute_materials=底稿可由學員自由手繪輪廓；撕紙材料可用舊雜誌大色塊替代。; rationale=撕紙的聲音與阻抗是天然的負向情緒宣洩途徑。將煩惱寫於紙背後撕碎，再重新拼貼成美麗畫作，象徵情緒轉化與自我療癒。; goals=System.Object[]; space_setup=方桌圍坐，每人發放一個乾淨托盤放置撕下的小紙片，背景播放放鬆輕音樂。; process=System.Object[]; grading_down=提供粗線條簡單圖形（如大茶壺、兔子）；允許撕大片紙塊直接拼貼。; grading_up=挑戰複雜羽毛或波浪漸層圖案（海豚、向日葵），要求微型馬賽克細緻填色。; safety=引導情緒撕紙為安全象徵動作，避免學員產生過激崩潰反應，適時給予同理陪伴。; tags=System.Object[]}.population))
- 主要介入能力：感覺處理與情緒調節、精細動作與手部協調
- 建立檔案：wiki/activities/comm-psych-tear-art-therapy.md`n
## [2026-11-11] ingest | 社牛養成計畫 — 日間病房五週全方位社交技巧訓練 (comm-psych-social-skills-master)
- 適用族群：社區精神復健 ($(@{id=comm-psych-social-skills-master; title=社牛養成計畫 — 日間病房五週全方位社交技巧訓練; population=community-psychiatry; population_name=社區精神復健; duration=75分鐘; group_size=10-15人; skills=System.Object[]; materials=System.Object[]; substitute_materials=情境影片可用帶領者真人即興短劇示範；眼罩可用絲巾或帽子遮光替代。; rationale=結合職能治療介入策略（OTIPM）、人際互動溝通技能評估（ACIS）與團體動力學，全方位培養精神復健學員之社交實戰技能。; goals=System.Object[]; space_setup=分組圓桌配置，中央設有角色扮演即興舞台，各組配備文具盒與計時器。; process=System.Object[]; grading_down=自我介紹提供填空範本；衝突情境劇由治療師擔任主角帶領對話。; grading_up=隨機給予高難度衝突情境，要求學員即興運用換位思考化解僵局。; safety=角色扮演嚴禁人身攻擊或舊傷揭露；維持安全包容、互相信任之團體心理防線。; tags=System.Object[]}.population))
- 主要介入能力：社交互動與團體合作、執行功能與認知規劃
- 建立檔案：wiki/activities/comm-psych-social-skills-master.md`n
## [2026-11-11] ingest | 化垃圾為藝術品 — 環保回收物立體再生創作 (comm-psych-recycled-art)
- 適用族群：社區精神復健 ($(@{id=comm-psych-recycled-art; title=化垃圾為藝術品 — 環保回收物立體再生創作; population=community-psychiatry; population_name=社區精神復健; duration=70分鐘; group_size=8-12人; skills=System.Object[]; materials=System.Object[]; substitute_materials=可用回收紙箱瓦楞紙或鋁罐替代，裝飾可用落葉或毛線球。; rationale=精神復健強調自我賦權與環境永續。將回收物轉化為具生活實用性或情感象徵的立體藝術，培養6R環保認知與創意思維。; goals=System.Object[]; space_setup=工作桌分區陳列各類洗淨回收材料，備有安全剪裁專區與彩繪通風處。; process=System.Object[]; grading_down=提供已修剪平整之寶特瓶半成品，學員專注於包裝紙黏貼與彩繪外觀。; grading_up=挑戰使用多種異材質（塑膠、吸管、紙質）組裝出具活動關節的立體雕塑。; safety=所有回收物必須事先徹底清洗消毒；邊緣修剪平整防割傷。; tags=System.Object[]}.population))
- 主要介入能力：精細動作與手部協調、執行功能與認知規劃
- 建立檔案：wiki/activities/comm-psych-recycled-art.md`n
## [2026-11-11] ingest | 腦力激盪賓果賽 — 細節闡述與語意記憶活化團體 (geriatric-cognitive-bingo)
- 適用族群：高齡長照 ($(@{id=geriatric-cognitive-bingo; title=腦力激盪賓果賽 — 細節闡述與語意記憶活化團體; population=geriatric-care; population_name=高齡長照; duration=40分鐘; group_size=8-12人; skills=System.Object[]; materials=System.Object[]; substitute_materials=長輩若不便寫字，可提供預先印製好的大字體圖卡讓長輩挑選黏貼。; rationale=針對長照長輩，運用「細節闡述（Elaboration）」記憶策略，從功能、外觀與生活情境多維度描述物品，深化大腦語意編碼，活化長期記憶。; goals=System.Object[]; space_setup=兩組面對面圍坐，桌上備有大字版對照單，長輩配戴老花眼鏡確保視覺清晰。; process=System.Object[]; grading_down=縮小為3*3九宮格；由帶領者提供特徵選擇題輔助出題。; grading_up=不可講出直接用途，限制只能由「材質、觸感、氣味」等感官特徵描述。; safety=字體至少36pt以上；避免節奏過急引發挫折焦慮，重視參與同樂感。; tags=System.Object[]}.population))
- 主要介入能力：執行功能與認知規劃、社交互動與團體合作
- 建立檔案：wiki/activities/geriatric-cognitive-bingo.md`n
## [2026-11-11] ingest | 日常身體力學與下背痛防護 — 生活型態再造健康模組 (geriatric-body-mechanics-back)
- 適用族群：高齡長照 ($(@{id=geriatric-body-mechanics-back; title=日常身體力學與下背痛防護 — 生活型態再造健康模組; population=geriatric-care; population_name=高齡長照; duration=60分鐘; group_size=8-10人; skills=System.Object[]; materials=System.Object[]; substitute_materials=地面伸展可完全轉換為坐姿伸展操，毋需長輩躺臥地面。; rationale=許多長者受下背痛困擾。透過生活型態再造（Lifestyle Redesign）導入正確身體力學原則與溫和伸展，降低關節退化負擔，促進自主生活品質。; goals=System.Object[]; space_setup=椅子圍成半圓形，中央空出示範區，後方鋪設伸展軟墊，確保走道無障礙物。; process=System.Object[]; grading_down=長輩全程採坐姿進行伸展，避免臥姿上下墊子產生頭暈或關節疼痛。; grading_up=指導結合腹式深呼吸的骨盆核心微收縮，並發放居家生活姿勢自評表追蹤。; safety=嚴禁急速扭腰或劇烈後仰；嚴重骨鬆長者避免大幅度彎折脊椎；穿著防滑平底鞋。; tags=System.Object[]}.population))
- 主要介入能力：感覺處理與情緒調節、執行功能與認知規劃
- 建立檔案：wiki/activities/geriatric-body-mechanics-back.md`n
## [2026-11-11] ingest | 葉來葉好玩 — 綠意園藝觸覺感官與休閒藝術團體 (geriatric-horticultural-therapy)
- 適用族群：高齡長照 ($(@{id=geriatric-horticultural-therapy; title=葉來葉好玩 — 綠意園藝觸覺感官與休閒藝術團體; population=geriatric-care; population_name=高齡長照; duration=60分鐘; group_size=8-12人; skills=System.Object[]; materials=System.Object[]; substitute_materials=若無新鮮植物可用乾燥落葉或壓花替代；藤編條可用粗毛線替代。; rationale=依據園藝治療CARE動能模式（串連、活動、反思、經驗），親手觸摸泥土與植物芬芳，能喚醒長輩自然生命力，舒緩身心焦慮。; goals=System.Object[]; space_setup=播放森林蟲鳴BGM，長桌鋪設防污桌巾，整齊擺放洗淨植物與畫具。; process=System.Object[]; grading_down=提供葉脈深厚的大葉欖仁直接刷水彩拓印；由志工協助固定葉片。; grading_up=結合細緻藤編穿編與小果實鑲嵌，製作立體浮雕式園藝風景壁畫。; safety=確認植物絕對無毒、無刺毛與過敏汁液；使用藤編時注意防範木屑細刺。; tags=System.Object[]}.population))
- 主要介入能力：感覺處理與情緒調節、精細動作與手部協調
- 建立檔案：wiki/activities/geriatric-horticultural-therapy.md`n


## [2026-11-11] purge | 依使用者要求清除 4 篇初始預設非真實資料活動
- 刪除活動檔案：`sensory-clay-planet.md`, `expressive-emotion-collage.md`, `community-baking-workshop.md`, `reminiscence-starlight-ball.md`。
- 刪除草稿來源：`sources/clinical-notes-2026.md`。
- 確保全站知識庫 100% 來自使用者上傳之 22 份真實教案。

## [2026-11-11] batch-split-ingest | 22 份教案精細拆分與 38 篇獨立活動入庫
- **拆分原則**：將各計畫書內之獨立小活動（如動態遊戲、手功能創作、五週單元）完整分離為具備獨立教學目標與分級調適之獨立教案。
- **拆分成果統計**：
  - 兒童職能（pediatrics）：12 篇獨立活動（涵蓋動態平衡、球類、撕貼、輕黏土、手作風車、食物拼圖、運幣）。
  - 精神科病房（psychiatric-inpatient）：10 篇獨立活動（生活問答、紙燈籠、猜燈謎、立體櫻花、剪紙櫻花、棒球衣摺紙、球場情境、幸運草心形葉、立體紙蝴蝶、螢火蟲）。
  - 社區精神復健（community-psychiatry）：12 篇獨立活動（食物紅綠燈、均衡餐盤大廚、九宮格應變、立體星芒、聖誕心願襪、撕紙肌理藝術、社牛養成五週方案 5 篇、環保寶特瓶多肉盆栽）。
  - 高齡長照（geriatric-care）：4 篇獨立活動（腦力激盪九宮格賓果、身體力學搬物防跌、居家座椅下背痛伸展、草木五感園藝治療）。
- **結構標準化**：全數 38 篇活動嚴格遵循 5 大模組（理念目標、道具場地、流程步驟、Grading Down/Up、安全注意事項），並同步支援「團體類型」（藝術、認知、生活功能、社交、動作）與「跨族群適用」雙重維度。
- **同步更新**：已同步寫入 `data/activities.json`、`wiki/activities/*.md`、`wiki/index.md`。


## [2026-11-12] refine | 依治療師專業反饋調整活動拆分與族群適用性（共 32 篇）
- **兒童職能調整**：第一週、第二週、第三週、第四週計畫書之第二/三個活動（紙杯花藝、撕貼畫、輕黏土、紙杯風車）確立為「兒童專屬」。
- **精神科病房合併與調適**：
  - `0312手工藝` 不須拆分，整併為「櫻花盛開（手部精細摺紙與春季立體剪紙櫻花藝術）」。
  - `0319手工藝` 不須拆分，整併為「澄清湖棒球回憶（球衣球帽摺紙與棒球縫線情境創作）」，刪除認知益智與兒童職能標籤，加入高齡長照適用。
  - `0407活動企劃` 不須拆分，整併為「手功能活動-幸運草（立體心形葉、捲紙莖與翩翩彩蝶創作）」。
  - `0421手功能` 螢火蟲手功能活動加入高齡長照適用。
- **社區精神復健合併與調適**：
  - `0326益智` 不須拆分，整併為「『營』在起跑點（食物紅綠燈考驗與均衡餐盤大廚師）」。
  - `呈泰第一次` 應變達人九是你刪除精神科病房標籤。
  - `呈泰第二次` 不須拆分，整併為「聖誕『星』願滿天飛（立體星芒雪花與聖誕心願襪拼貼）」，刪除精神病房與兒童職能標籤。
- **高齡長照合併**：
  - `衰弱老人生活型態再造` 不須拆分，整併為「日常身體力學與下背痛防護（日常生活搬物防跌與座椅核心伸展）」。
- **全站獨立活動總篇數**：定錨為 32 篇，已同步更新所有 Markdown、JSON 與成果網頁。


## [2026-11-12] refine | 精神科病房三大次族群細分、適用人數核定與跨族群標籤符號統一
- **精神科病房深度細分**：依臨床實務與教案場域，正式劃分為：
  1. `psychiatric-acute`（精神科急性病房，如高雄長庚 12K/11K，收錄 0209益智、0223手工藝、0302益智共 3 篇）。
  2. `psychiatric-chronic`（精神科慢性/復健病房，如高雄長庚 10K/交誼廳，收錄 0312手工藝、0319手工藝、0407活動企劃、0421手功能共 4 篇）。
  3. `psychiatric-day`（精神科日間病房，如高雄長庚 10K日間病房、高醫/小港日間病房，收錄 0326健康餐盤、第 04 組社牛養成 5 週共 6 篇）。
- **活動適用人數核實**：
  - 根據 22 份原始 PDF 計畫書內文（如 0407 註明準備 25 人份、0421 註明準備 20 人份、0223 底稿 30 份、0302 分 3-6 組 15-30 人、第一週兒童 6-8 人/現場 7 人等）精確校正 32 項活動之建議人數。
  - 對於自由參與或無明確人數上限之教案（0209、呈泰第一次、第九組），詳列臨床依據並提出確認。
- **跨族群標籤與符號統一**：
  - 全面取消跨族群標籤的 `🔄` 符號與次等樣式，統一採用與主要族群相同之專屬徽章與 Emoji。
  - 全站徹底移除「適用」二字，呈現乾淨專業之族群名稱（如「👵 高齡長照」、「🌿 精神科慢性/復健病房」）。
- **知識庫雙向同步**：
  - 更新 `data/activities.json`、`wiki/activities/*.md` (32篇)。
  - 新增 `wiki/populations/psychiatric-acute.md`、`psychiatric-chronic.md`、`psychiatric-day.md`，更新 `community-psychiatry.md`、`geriatric-care.md`、`pediatrics.md` 與 `psychiatric-inpatient.md`。
  - 更新 `wiki/index.md` 索引總矩陣。


## [2026-11-12] refine | 精神科病房三大病房準確對照（10K急性、11K日間、12K慢性）與特定教案人數微調
- **精確病房別與活動歸屬校正**：
  - **10K 為精神科急性病房（`psychiatric-acute`）**：收錄 `0407` 幸運草手作（15-20人）、`0421` 微光螢火蟲（15-20人）。
  - **11K 為精神科日間病房（`psychiatric-day`）**：收錄 `0312` 立體櫻花（20-25人）、`0319` 棒球回憶（20-25人）、`0326` 健康餐盤（20-25人），以及第 04 組社牛養成五週方案（12-20人）。
  - **12K 為精神科慢性病房（`psychiatric-chronic`）**：收錄 `0209` 生活問答（20-25人）、`0223` 喜慶紙燈籠（20-30人）、`0302` 迎春猜燈謎（20-25人）。
- **依治療師指示微調人數**：
  - `0417活動計畫書`：更新為 **6~8人**。
  - `0424活動計畫書`：更新為 **6~8人**。
  - `0209益智計畫書`：更新為 **20~25人**。
  - `0302益智計劃書`：更新為 **20~25人**。
  - `0407活動企劃書`：更新為 **15~20人**。
  - `呈泰第一次活動`：更新為 **10~20人**。
  - `呈泰第二次活動`：更新為 **10~20人**。
  - `呈泰第三次活動`：更新為 **10~20人**。
  - `第九組計畫書`：更新為 **5~10人**。
  - `第八組團體計畫書`：更新為 **20~40人**。
- **全站同步**：
  - 更新 `data/activities.json`、`index.html`（含內建 Fallback 資料庫）。
  - 更新 `wiki/activities/*.md` (32篇)。
  - 更新 `wiki/populations/` 專屬導引（`psychiatric-acute.md`、`psychiatric-chronic.md`、`psychiatric-day.md`、`psychiatric-inpatient.md`、`pediatrics.md`、`community-psychiatry.md`、`geriatric-care.md`）。
  - 更新 `wiki/index.md` 索引總矩陣。
