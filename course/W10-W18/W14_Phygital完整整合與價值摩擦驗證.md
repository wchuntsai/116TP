# 數位教具開發實務｜第 14 週

# Phygital 完整整合：實體 × Web AR 的價值與摩擦驗證

## 不是把兩種媒介放在一起，而是讓它們形成一個不可任意拆解的學習循環

**授課時間：**120 分鐘\
**前置成果：**W13 Web AR MVP v0.3、Human Verification、Micro-test
evidence、W14 Phygital Integration Ticket\
**本週核心：**Physical → Trigger → Digital Extension → Interaction →
Return → Physical Action → Learning/Game Consequence\
**技術定位：**本週原則上不新增 Web AR、Firebase 或 AI
功能；重點是整合、刪除、驗證與收斂。\
**最低成果：**完成 Phygital Prototype
v1.0、一次完整流程測試、Value--Friction Evidence
Map，以及一項有證據支持的最終整合決策。

> 「有實體＋有 AR」不等於 Phygital integration。\
> 真正的整合是：**實體情境產生資訊需求，數位層提供必要擴展，數位互動再改變玩家回到實體後的行動。**

------------------------------------------------------------------------

# Part A｜教師教案

## 一、W10--W14 的完整設計鏈

  --------------------------------------------------------------------------------------
  週次                    核心問題                主要產出
  ----------------------- ----------------------- --------------------------------------
  W10                     Why Web AR?             Information Need、AR Necessity、Media
                                                  Decision

  W11                     How little AR is        Trigger→Extension→Interaction→Return
                          enough?                 MVP

  W12                     Does it actually help?  Controlled Revision、Evidence
                                                  Question、Comparison

  W13                     What should the digital AI-assisted Content＋Human
                          layer say/show?         Verification

  W14                     Do physical and digital Phygital Prototype v1.0＋完整流程證據
                          really complement each  
                          other?                  
  --------------------------------------------------------------------------------------

W14 不再追求功能增加，而是做三件事：

**Connect → Remove → Validate**

------------------------------------------------------------------------

## 二、本週學習目標

學生完成 W14 後應能：

1.  描述完整 Physical--Digital--Physical learning/game loop。
2.  判斷每一段資訊與操作應留在實體或數位端的理由。
3.  找出實體與數位之間的 handoff friction。
4.  使用 Removal Test 判斷 AR 是否具有必要價值。
5.  以完整玩家流程而非單一 AR 畫面進行測試。
6.  同時蒐集 learning/game value 與 digital friction 證據。
7.  依證據做 Keep / Revise / Remove / Reassign 的整合決策。
8.  形成可帶入 W15 批判性 AI 協作自評的設計歷程證據。

------------------------------------------------------------------------

## 三、120 分鐘流程

  ---------------------------------------------------------------------------------------------------
  時間           階段              教師／TA                       學生活動             產出
  -------------- ----------------- ------------------------------ -------------------- --------------
  0--10          Integration Reset 強調本週不加功能               整理 v0.3 與實體     Test Build
                                                                  Prototype            

  10--25         Phygital Loop Map 示範七節點完整循環             畫完整流程           Loop Map

  25--40         Handoff Audit     示範實體→數位、數位→實體交接   找斷點與重複資訊     Handoff Map

  40--52         Removal Test      問「拿掉                       執行雙向移除檢核     Necessity
                                   AR／實體會失去什麼？」                              Evidence

  52--65         Value--Friction   定義 value 與 friction 指標    完成測試表           Test Plan
                 Plan                                                                  

  65--90         Full-flow         要求不拆開測單一畫面           另一組完成完整流程   Observation
                 Playtest                                                              Evidence

  90--103        Player Debrief    追問媒介切換與學習行動         訪談玩家             Player Voice

  103--113       Integration       引導                           做最終整合判斷       Decision
                 Decision          Keep/Revise/Remove/Reassign                         Matrix

  113--120       W15 Bridge        收斂 AI/人類角色證據           個人 exit reflection W15 Evidence
                                                                                       Pack
  ---------------------------------------------------------------------------------------------------

------------------------------------------------------------------------

# Part B｜核心概念 1：Phygital Loop

本週用七個節點檢查完整設計：

  節點                      設計問題
  ------------------------- ------------------------------------------
  1\. Physical Context      玩家在實體端正在做什麼？
  2\. Trigger Need          什麼情境使玩家需要額外資訊？
  3\. Digital Extension     數位層新增什麼實體難以承載的價值？
  4\. Digital Interaction   玩家在數位端仍需要做什麼判斷／操作？
  5\. Return Cue            玩家如何知道該離開數位層？
  6\. Physical Action       回到實體後，玩家做什麼不同的行動？
  7\. Consequence           這個行動如何影響學習、遊戲或下一輪決策？

如果第 7 節點無法回扣第 1 節點，數位層可能只是附加內容，而非整合。

------------------------------------------------------------------------

# Part C｜學生學習單 1：Phygital Loop Map

-   小組：
-   Prototype：v1.0
-   W13 Evidence ID：
-   核心 Extension Claim：

  節點                  玩家行為   資訊在哪裡       設計理由   可觀察證據
  --------------------- ---------- ---------------- ---------- ------------
  Physical Context                 實體                        
  Trigger Need                     實體／交接                  
  Digital Extension                Web AR                      
  Digital Interaction              Web AR                      
  Return Cue                       Web AR／交接                
  Physical Action                  實體                        
  Consequence                      實體／學習結果              

### 一句完整設計主張

> 玩家先在 \_\_\_\_\_\_，因為 \_\_\_\_\_\_ 產生資訊需求；Web AR 提供
> \_\_\_\_\_\_，玩家完成 \_\_\_\_\_\_ 後回到實體進行
> \_\_\_\_\_\_，因此預期 \_\_\_\_\_\_。

------------------------------------------------------------------------

# Part D｜核心概念 2：Handoff Audit

Phygital 問題常常不在實體或 AR 本身，而在「切換」。

## Physical → Digital

-   玩家知道何時該拿手機嗎？
-   Trigger 是否自然出現在需求發生時？
-   是否要中斷對話／遊戲才能操作？
-   多人共玩時誰拿裝置？
-   掃描前是否需要額外說明？

## Digital → Physical

-   玩家知道何時 AR 已完成任務嗎？
-   Return Cue 是否清楚？
-   數位結果是否真的影響實體下一步？
-   玩家是否因留在手機上而忘記桌面互動？
-   是否需要手動抄寫數位資訊回實體？

------------------------------------------------------------------------

# Part E｜學生學習單 2：Handoff Map

  交接點               玩家原本行為   預期行為   可能 friction   修正／fallback
  -------------------- -------------- ---------- --------------- ----------------
  Physical → Digital                                             
  Digital → Physical                                             

**最脆弱的交接點：**

**支持證據：**

**如果不修，會影響：**\
□內容理解　□玩家注意　□遊戲節奏　□同儕互動　□操作成功　□其他

------------------------------------------------------------------------

# Part F｜核心概念 3：雙向 Removal Test

## Test A｜拿掉 Web AR

假設完全移除 AR：

-   核心遊戲仍能進行嗎？
-   學習任務仍能完成嗎？
-   會失去哪一項「不可簡單由實體替代」的價值？
-   若只失去「比較酷」，AR 必要性不足。
-   若 QR／紙卡即可等效替代，需重新檢查媒介選擇。

## Test B｜拿掉實體

假設全部搬到手機：

-   會失去哪些觸覺、空間、共享視線、面對面互動？
-   哪些遊戲機制會變成單純按按鈕？
-   哪些內容理解依賴實體操作？
-   若完全數位化反而更合理，為什麼還需要實體？

> 好的 Phygital 設計不是「兩邊都很多」，而是兩邊各自承擔最適合的工作。

------------------------------------------------------------------------

# Part G｜學生學習單 3：Removal Test

  問題                                     結果              具體失去／保留的價值
  ---------------------------------------- ----------------- ----------------------
  拿掉 Web AR，核心流程還能進行？          □是 □否 □部分     
  拿掉 Web AR，會失去什麼？                                  
  QR／一般網頁能等效替代？                 □是 □否 □部分     
  拿掉實體，核心流程還能進行？             □是 □否 □部分     
  拿掉實體，會失去什麼？                                     
  實體與數位是否各有不可簡單替代的角色？   □是 □否 □不確定   

### 目前判斷

□互補關係清楚\
□AR 價值不足，需要刪減／移除\
□實體端價值不足，需要重設\
□兩邊資訊重複，需要重新分工\
□資料不足，需要完整流程測試

------------------------------------------------------------------------

# Part H｜Value--Friction Test Plan

本週不要只問「玩家喜不喜歡」。

## Value indicators

可選： - 玩家能完成原本卡住的學習／操作步驟 - 提示後仍保留必要思考 -
數位資訊能支持下一個實體決策 - 玩家更容易理解內容表徵 -
實體互動因數位資訊而更有意義 - Return 後能正確完成遊戲行動

## Friction indicators

可選： - 掃描失敗／等待 - 不知道何時使用 AR - 手機閱讀負擔 -
不知道何時回到實體 - 多人共看困難 - 注意力長時間停在手機 - 重複資訊 -
額外步驟大於新增價值

### 我們的主要 Value indicator：

### 我們的主要 Friction indicator：

### 我們的 Evidence Question：

> 在完整 Physical→Digital→Physical 流程中，\_\_\_\_\_\_ 是否能在不造成
> \_\_\_\_\_\_ 的情況下，支持玩家 \_\_\_\_\_\_？

------------------------------------------------------------------------

# Part I｜Full-flow Playtest

## 測試規則

1.  測試者從實體遊戲開始，不從 AR 畫面開始。
2.  設計組不口頭補充正式版本沒有的說明。
3.  完整走過 Trigger、AR、Return 與後續實體行動。
4.  觀察者記錄「媒介切換」與「玩家行為」，不是只記 bug。
5.  若技術失效，記錄 fallback 是否有效。
6.  測試後才訪談。

## 行為紀錄

  ------------------------------------------------------------------------------
  時間        節點          玩家行為    是否停頓／求助   Value       Friction
                                                         evidence    evidence
  ----------- ------------- ----------- ---------------- ----------- -----------
              Physical                                               

              Trigger                                                

              Digital                                                

              Return                                                 

              Physical                                               
              Action                                                 

              Consequence                                            
  ------------------------------------------------------------------------------

------------------------------------------------------------------------

# Part J｜Player Debrief

請保留玩家原句。

1.  你在什麼時候覺得需要使用 AR？
2.  AR 提供了什麼實體上沒有的幫助？
3.  哪一次拿手機最打斷原本的活動？
4.  看完 AR 後，你知道要回到實體做什麼嗎？
5.  如果完全拿掉 AR，你最明顯會失去什麼？
6.  如果全部改成手機遊戲，你最明顯會失去什麼？
7.  哪個資訊其實放錯媒介了？

**關鍵玩家原句 1：**

**關鍵玩家原句 2：**

------------------------------------------------------------------------

# Part K｜Integration Decision Matrix

每個重要元件做一項決定。

  元件／資訊   Evidence   決策                              理由
  ------------ ---------- --------------------------------- ------
                          □Keep □Revise □Remove □Reassign   
                          □Keep □Revise □Remove □Reassign   
                          □Keep □Revise □Remove □Reassign   
                          □Keep □Revise □Remove □Reassign   

### Reassign 是什麼？

不是刪掉資訊，而是把它移到更適合的媒介。

例如： - AR 中的核心規則 → 移回實體卡面 - 卡面塞不下的分層提示 → 留在
AR - 長篇背景故事 → 改成非必要延伸頁 - AR 中的「下一步」 → 改成更明確的
Return Cue

------------------------------------------------------------------------

# Part L｜Prototype v1.0 Integration Summary

**實體端負責：**

**Web AR 負責：**

**AI 在最終版本中的角色：**

**Firebase／event logging 在最終版本中的角色（若有）：**

**Physical → Digital 的交接：**

**Digital → Physical 的交接：**

**最重要的 learning/game value：**

**最大的 digital friction：**

**目前仍未解決的問題：**

------------------------------------------------------------------------

# Part M｜個人 Exit Reflection

請個人作答。

1.  W10 時，我原本認為 AR 最適合用來：
2.  經過 W11--W14，我現在認為「需要 AR」至少必須符合：
3.  一個我曾想加入、最後卻刪除／移回實體的功能是：
4.  讓我改變想法的 evidence 是：
5.  在這次設計中，哪個判斷最不能交給 AI 或系統自動決定？為什麼？
6.  如果下一次重新設計，我會先問的問題是：

------------------------------------------------------------------------

# Part N｜W14 Rubric（100 分）

> 本週評量完整媒介整合與證據推理，不評 AR 功能數量。

  -------------------------------------------------------------------------------------------------------------------------------
  構面                       權重 Level 4                                            Level 3        Level 2      Level 1
  ---------------- -------------- -------------------------------------------------- -------------- ------------ ----------------
  Phygital Loop                20 七節點形成清楚循環，數位結果實際改變實體後續行動   流程大致完整   有斷點       實體與 AR
  完整性                                                                                                         各自獨立

  實體／數位分工               20 能以內容、玩家與媒介特性說明分工，且通過 Removal   分工合理       部分重複     以功能多寡分工
                                  Test                                                                           

  Handoff 與                   15 能辨識雙向交接摩擦並有證據／fallback               有具體處理     問題較表面   忽略交接
  friction                                                                                                       

  Full-flow                    20 完整流程測試，同時蒐集 value 與 friction 行為證據  有完整測試     主要測單一   只展示作品
  Evidence                                                                                          AR 畫面      

  Integration                  15 Keep/Revise/Remove/Reassign 均有 evidence 支持     多數有理由     偏主觀       不願刪除功能
  Decision                                                                                                       

  個人設計反思                 10 能指出觀點改變、證據來源與不可自動化的設計判斷     反思具體       偏描述過程   只描述做了什麼
  -------------------------------------------------------------------------------------------------------------------------------

### 評分提醒

-   刪除 AR 功能可能是高品質整合決策。
-   AR 內容越多不代表整合越好。
-   技術失效但有合理 fallback、能保留測試證據，不等於設計失敗。
-   最終作品完成度與 TPACK evidence 是不同層次，不應互相替代。

------------------------------------------------------------------------

# Part O｜附加教材：Phygital Anti-pattern Cards

### 1. Scan Everything

每張卡都要掃，但說不出為什麼。

### 2. Digital Duplicate

AR 只是重複卡面資訊。

### 3. Phone Gravity

玩家進入手機後很久不回桌面。

### 4. Broken Return

看完 AR 後不知道下一步。

### 5. Physical Decoration

實體只剩掃描標記，真正活動都在手機。

### 6. AR Decoration

3D、動畫、AI 圖像很吸睛，但不影響學習／遊戲決策。

### 7. No-fallback Dependency

任何小型技術故障都讓整個教具停擺。

### 8. Evidence-free Attachment

保留某功能的理由只有「我們花很多時間做」。

------------------------------------------------------------------------

# Part P｜教師／研究者：TPACK Evidence Coding

## 建議 Evidence Unit

**prior evidence → physical/digital allocation → tradeoff → full-flow
behavior → integration decision**

  ---------------------------------------------------------------------------------------
  W14 evidence                          TPACK 候選碼            reasoning code
  ------------------------------------- ----------------------- -------------------------
  說明 Web AR 技術限制與 fallback       TK                      digital_friction

  依玩家注意／同儕互動決定媒介切換      TPK                     learner_attention /
                                                                interaction_tradeoff

  依特定內容表徵決定實體或 AR           TCK                     media_translation /
                                                                content_alignment

  保留特定內容的學習思考而刪除自動化    PCK / TPK               automation_boundary

  以 Removal Test 重新分配資訊          TCK / TPK               design_tradeoff /
                                                                media_translation

  依完整流程 evidence 刪除或回退功能    TPK / TCK /             evidence_based_revision
                                        TPACK_candidate         

  同時整合內容、學習者、實體優勢、Web   TPACK_candidate         integration_reasoning /
  AR 特性與證據                                                 design_tradeoff

  能指出 event/AI/AR 的證據與推論界線   PK / TPK /              evidence_boundary
                                        TPACK_candidate         
  ---------------------------------------------------------------------------------------

### 編碼界線

-   「作品同時有實體與 AR」不構成 TPACK。
-   「AR 很方便、卡片很有手感」仍可能只是媒介特徵描述。
-   若學生能說明「哪個內容為何留在實體、哪個資訊為何由 AR
    擴展、這樣如何改變玩家行動，並用測試證據修正」，才是較完整的整合證據。
-   W14 適合觀察 `integration_reasoning`，但正式納入穩定 codebook
    前仍應做跨案例檢查。

------------------------------------------------------------------------

# Part Q｜Firebase 建議欄位

``` text
student_id
team_id
week = 14
evidence_id
source_type = loop_map | handoff_audit | removal_test | full_flow_test | player_voice | integration_decision | exit_reflection
prior_evidence_ref
prototype_version = v1.0
loop_node
medium = physical | web_ar | transition
design_claim
value_indicator
friction_indicator
observed_behavior
player_quote
removal_result
integration_decision = keep | revise | remove | reassign
decision_reason
fallback
primary_code
secondary_codes
design_reasoning
evidence_strength
observed = true
coding_version = TPACK_Evidence_v1.0
```

若 W12--W14 已有 `learning_events`，保留原始 event；不要為了 W14
再增加與 Evidence Question 無關的追蹤欄位。

------------------------------------------------------------------------

# Part R｜ENA 銜接

W14 semantic unit 建議採 **integration episode**：

`W10 necessity → W11 MVP → W12 revision → W13 content decision → W14 integration decision`

也可以用 W14 單週的同一個「媒介分工／交接問題」作 stanza。

可能共現：

`TCK ↔ media_translation ↔ content_alignment`

`TPK ↔ learner_attention ↔ interaction_tradeoff ↔ digital_friction`

`evidence_based_revision ↔ design_tradeoff ↔ integration_reasoning`

`PCK ↔ TCK ↔ TPK ↔ TPACK_candidate`

### 研究解讀提醒

-   ENA 顯示的是 code co-occurrence 結構，不是「TPACK 高低排行榜」。
-   W14 的網絡變化可與 W10 起始 evidence 比較，但要保留不同任務提供不同
    evidence opportunity 的限制。
-   沒有出現某 code，不等於學生沒有該能力；先檢查任務是否提供觀察機會。
-   `entry_week` 前仍為 NA，不補 0。

------------------------------------------------------------------------

# Part S｜W14 → W15 橋接

W14 結束後，每位學生／小組應保留：

1.  Phygital Prototype v1.0；
2.  七節點 Phygital Loop Map；
3.  Handoff Audit；
4.  雙向 Removal Test；
5.  Value--Friction Full-flow Test；
6.  玩家原句；
7.  Keep / Revise / Remove / Reassign Decision；
8.  個人 Exit Reflection。

W15 不需要再教一批 AI 功能。下一步應回頭檢查整個 W3--W14 的 AI 協作：

**AI
在哪些地方真正擴展了設計能力？哪些地方學生只是接受建議？哪些判斷必須由人類根據內容、學習者、媒介與
evidence 負責？**

這將把「AI 使用紀錄」轉成可分析的 **AI--human design judgment
evidence**，並為 W16 的總結性同儕測試與 ENA--TPACK 歷程分析做準備。