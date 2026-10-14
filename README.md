# 116TP｜數位教具開發實務 × TPACK × ENA

本儲存庫用於管理「數位教具開發實務」課程教材與研究設計，核心關注學生在實體教具、Web AR、AI 協作與證據驅動迭代歷程中的 TPACK 發展。

## 課程後半段設計主軸

W10–W18 採以下漸進架構：

1. **W10｜AR 必要性判斷**：Physical Information Audit → AR Necessity → Media Choice
2. **W11｜最小可驗證 Web AR**：Trigger → Extension → Interaction → Return
3. **W12｜證據驅動迭代**：Evidence → One-variable Revision → Minimal Logging → Compare
4. **W13｜AI × Web AR 內容設計**：AI Generate → Human Verify → Web AR Fit
5. **W14｜Phygital 完整整合**：Physical → Digital → Return → Consequence
6. **W15｜AI–Human Judgment**：Adopt / Modify / Reject / Boundary
7. **W16｜總結性同儕測試與 ENA–TPACK 歷程解讀**
8. **W17｜期末發表**：Prototype vFinal + Final Evidence Story
9. **W18｜總結性 ENA–TPACK 分析與焦點訪談**

## 研究原則

- Firebase / Web Augment 原始事件不是 TPACK 分數。
- 學生作品分數、AI 使用次數與 ENA 線條數量都不直接等於 TPACK 高低。
- 研究以 evidence unit 為基本分析單位，正式 coding 與學生自我標記分開處理。
- ENA 使用 code co-occurrence 分析知識與 reasoning codes 的連結結構。
- 缺失值區分：`NA` = 無觀察機會；`0` = 有觀察機會但 code 未出現。
- AI、Web AR、Firebase 均以「是否回應真實設計問題」為導入前提，不為技術而技術。

## 目錄

```text
116TP/
├─ README.md
├─ course/
│  └─ W10-W18/
├─ research/
│  ├─ TPACK_Evidence_Codebook/
│  ├─ ENA/
│  ├─ Firebase/
│  └─ Interview/
├─ dify/
│  └─ knowledge_base/
└─ materials/
```

目前已同步 W10–W18 的新版 Markdown 教材。後續可逐步加入 W1–W9、正式 codebook、ENA 前處理規則、Firebase schema、Dify/RAG 知識庫與研究文件。
