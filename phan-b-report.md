# PHẦN B — BUỔI CHIỀU · Chọn hướng chuyên sâu
**Họ tên:** Nguyễn Thái Dương &nbsp;&nbsp;&nbsp;&nbsp; **MSSV:** 2A202600823 &nbsp;&nbsp;&nbsp;&nbsp; **Pathway:** A — Tìm / chuyển việc &nbsp;&nbsp;&nbsp;&nbsp; **Track dự kiến:** T3 · AI Engineering

---

## B1 · Ghi chú Research Thị Trường Tương Lai (Bộ câu hỏi 4)

> Nguồn tham khảo: WEF Future of Jobs 2025, Microsoft 2026 Work Trend Index, PwC 2026 Global AI Jobs Barometer, Stanford HAI 2026 AI Index, ITviec Vietnam IT Market 2025–2026.

### Nghề / kỹ năng đang tăng nhanh

| Kỹ năng / Nghề | Tín hiệu cụ thể |
|---|---|
| AI/LLM Engineer | Nhu cầu tăng 3–5× trong 2 năm; hầu hết công ty tech đều mở headcount mới |
| Prompt Engineering & Evaluation | Từ không tồn tại → role riêng biệt tại các công ty AI lớn |
| RAG & Knowledge Systems | Gần như mọi enterprise AI project đều cần; demand vượt người có kinh nghiệm thực chiến |
| Multi-agent Orchestration | Còn mới nhưng tăng nhanh; các framework LangGraph, CrewAI, AutoGen đang scale |
| AI Reliability / Guardrails | Khi AI vào production, cần người biết eval, test, và kiểm soát output |
| MLOps / LLMOps | Cầu tăng mạnh do nhiều model ra production nhưng thiếu người vận hành bền vững |

### Nghề / kỹ năng đang khan (cầu vượt cung)

- **AI Engineer có kinh nghiệm production-grade**: Nhiều người biết gọi API, nhưng ít người biết build hệ thống agent chạy ổn định, có eval, có fallback.
- **AI Evaluation Engineer**: Biết thiết kế benchmark, đánh giá LLM output, detect hallucination — cực khan tại Việt Nam.
- **Vietnamese-domain AI specialist**: Hiểu dữ liệu tiếng Việt, fine-tuning cho Vietnamese NLP — lợi thế địa phương rõ ràng.
- **AI Security / Red-teaming**: Prompt injection, jailbreak defense — nhu cầu tăng nhưng cung gần như bằng 0.

### Điều bất ngờ — năng lực đang bị định giá lại

- **Bất ngờ 1:** Kỹ năng "biết code" không còn là lợi thế cốt lõi — AI sinh code nhanh và khá tốt rồi. Thứ được trả lương cao bây giờ là *hiểu hệ thống đủ để review, debug, và quyết định architecture* khi AI đưa ra kết quả sai.
- **Bất ngờ 2:** PwC AI Jobs Barometer 2026 cho thấy mức lương AI-augmented roles tăng **trung bình 25–40%** so với roles không dùng AI — cùng title, khác năng lực, khác lương.
- **Bất ngờ 3:** ITviec 2025–2026: tại Việt Nam, AI Engineer fresher có thể bắt đầu 15–20 triệu/tháng nếu có portfolio thực, so với Software Engineer fresher thông thường 10–14 triệu — gap này sẽ lớn thêm.

### Một câu tổng kết

> **Thị trường tương lai thưởng cho người vừa hiểu đủ kỹ thuật để build production AI system, vừa biết đặt câu hỏi đúng để đánh giá khi hệ thống đó sai.**

---

## B2 · Ghi chú Research Role 2 Chiều (Bộ câu hỏi 5)

**Role chọn:** AI/LLM Application Engineer *(phổ biến tại Việt Nam dưới các tên: AI Engineer, LLM Engineer, Conversational AI Developer)*

**JD tham khảo:** 3 JD thật từ thị trường Việt Nam và quốc tế (VNG, FPT AI Center, các startup AI vừa nhận Series A)

---

### BÊN NGOÀI — Role này đòi hỏi gì

#### 4–6 kỹ năng / năng lực JD nhắc nhiều nhất

| # | Kỹ năng | Tần suất trong JD |
|---|---|---|
| 1 | Python thành thạo, quen LangChain / LlamaIndex / LangGraph | Gần như 100% JD |
| 2 | Thiết kế và triển khai RAG pipeline (chunking, embedding, retrieval, reranking) | ~90% JD AI Engineer |
| 3 | Prompt engineering, prompt chaining, system prompt design | ~85% |
| 4 | API integration: OpenAI, Anthropic, Gemini + cost/token management | ~80% |
| 5 | Vector database: Chroma, Pinecone, Weaviate, pgvector | ~75% |
| 6 | Evaluation & testing LLM output (custom eval scripts, Ragas, LangSmith) | ~60% — tăng nhanh |

#### Mức seniority và kỳ vọng portfolio

- **Fresher / Junior (0–1 năm):** Cần ít nhất 1–2 project end-to-end có thể demo; biết call API, build RAG cơ bản, hiểu token limit.
- **Kỳ vọng portfolio:** Một chatbot hoặc agent có RAG; một project có eval đo được (không chỉ "chạy được"); code trên GitHub với README rõ ràng.
- **Điều nhiều fresher bỏ qua:** JD đều hỏi về *error handling và fallback khi LLM trả kết quả tệ* — không chỉ hỏi "build được không" mà hỏi "làm gì khi nó sai".

---

### BÊN TRONG — Đối chiếu với chính mình (từ Phase 1)

#### Kỹ năng đã chạm ở Phase 1

| Kỹ năng JD đòi | Đã chạm ở Phase 1 | Artifact minh chứng |
|---|---|---|
| Python + LangChain | Có — D3–D4 dùng LangChain/LangGraph | Lab D3: ReAct agent; Lab D4: tool calling |
| RAG pipeline | Có — D8–D9 | Lab D8: RAG cơ bản; Lab D9: supervisor-worker |
| Prompt engineering | Có — xuyên suốt Phase 1 | Nhiều lab từ D1 trở đi |
| Multi-agent pattern | Có — D9 | Supervisor-worker architecture lab |
| API integration | Có — hầu hết lab | Các lab gọi OpenAI/Anthropic API |
| Vector DB | Chạm — D8 | Dùng Chroma trong RAG lab |
| Evaluation / Guardrails | Chưa sâu | Chưa có artifact eval rõ ràng |
| Observability / Logging | Mỏng | Có D10 nhưng chưa thành thục |

#### Kỹ năng cần đào sâu

- **Evaluation framework** (Ragas, LangSmith, custom eval): chưa có artifact nào đo được chất lượng output
- **Production reliability**: error handling, retry logic, fallback khi model trả kết quả tệ
- **Fine-tuning / alignment**: chưa chạm (LoRA/QLoRA/DPO — dự kiến Phase 2)
- **Vector store nâng cao**: reranking, hybrid search, metadata filtering

#### Kỹ năng chưa có

- GraphRAG (knowledge graph + RAG)
- Multi-agent production-grade (LangGraph phức tạp hơn lab cơ bản)
- MCP (Model Context Protocol)
- LLMOps / CI-CD cho AI system

#### Phần công việc có cho mình năng lượng không?

- **Có năng lượng:** Debug agent khi nó làm sai, thiết kế tool schema, xây RAG và quan sát chất lượng retrieval cải thiện từng bước — những phần này trong D3/D8/D9 tạo ra cảm giác "muốn tiếp tục đào sâu".
- **Ít năng lượng hơn:** Phần business case, stakeholder communication — không phải thế mạnh hiện tại.

### Một câu kết

> Role **AI/LLM Application Engineer** nghiêng rõ về **T3 · AI Engineering**, vì đòi hỏi đúng những kỹ thuật đã chạm ở D3–4 và D8–9, và gap còn lại (eval, fine-tuning, production reliability) đều là nội dung Phase 2 của T3.

---

## B3 · Track Decision Memo

```
TRACK DECISION MEMO — Day 15
Họ tên: Nguyễn Thái Dương · MSSV: 2A202600823   Pathway: A — Tìm / chuyển việc
```

---

### ① ĐỊNH HƯỚNG — vài job/role hướng tới + kỹ năng mỗi job đòi hỏi

| Job | Kỹ năng cần (từ JD thật) |
|---|---|
| AI/LLM Application Engineer | Python, LangChain/LangGraph, RAG, prompt engineering, vector DB, evaluation |
| AI Agent Developer | ReAct pattern, multi-agent orchestration, tool calling, MCP, reliability |
| AI Backend Engineer (LLM focus) | API integration, system design for AI, LLMOps, CI/CD, observability |

---

### ② ĐỐI CHIẾU BẢN THÂN — từ Phase 1

**Những việc mình đã làm được (liệt kê tự do):**

- Build ReAct agent từ đầu với LangChain (D3)
- Implement tool calling, thiết kế tool schema (D4)
- Dựng RAG pipeline: chunking → embedding → Chroma → retrieval → generation (D8)
- Thiết kế supervisor-worker multi-agent architecture (D9)
- Gọi và quản lý API key OpenAI/Anthropic, hiểu token/cost cơ bản
- Debug khi agent loop hoặc tool trả kết quả không đúng

**Loại công việc cho mình năng lượng, muốn làm tiếp:**

> Thiết kế và debug agent/RAG system — đặc biệt là khi tìm ra *tại sao* retrieval sai và fix được nó.

---

### ③ KỸ NĂNG MÌNH ĐỊNH PHÁT TRIỂN TỚI

**Ba kỹ năng ưu tiên:**
1. **LLM Evaluation** — Ragas, LangSmith, custom eval pipeline
2. **Production Agent Reliability** — error handling, fallback, retry, guardrails
3. **Fine-tuning cơ bản** — LoRA/QLoRA với model nhỏ

**Gap lớn nhất + thứ sẽ build để cho thấy tiến bộ:**

> Gap: chưa có artifact nào *đo được* chất lượng output AI một cách có hệ thống. Kế hoạch: build evaluation pipeline cho RAG project đã có — đo precision@k, faithfulness, answer relevancy bằng Ragas — để có con số cụ thể thay vì nhận xét cảm tính "trông có vẻ đúng".

---

### ④ QUYẾT ĐỊNH TRACK

**Track chọn: T3 · AI Engineering**

**Vì:**
> Trong Phase 1, phần cho mình nhiều năng lượng nhất là D3–4 (agent + tool calling) và D8–9 (RAG + multi-agent). Đúng là phần T3 tập trung nhất. Thị trường AI Engineering tại Việt Nam đang tăng mạnh và fresher có portfolio thực (agent chạy được, RAG có eval) có thể vào được — đây là lợi thế cạnh tranh rõ ràng so với fresher SW Engineer thông thường.

**Track cân nhắc nhưng KHÔNG chọn + lý lẽ mạnh nhất cho nó:**

> **T1 · AI Product** — Lý lẽ mạnh: thị trường thiếu người vừa hiểu kỹ thuật vừa ra quyết định sản phẩm, lương cao và ít cạnh tranh hơn AI Engineer thuần kỹ thuật. Tuy nhiên chưa chọn vì: mình chưa có kinh nghiệm thật với user research / business case / stakeholder — làm T3 trước để có nền tảng kỹ thuật vững, sau đó pivot sang Product dễ hơn chiều ngược lại.

**Dấu hiệu sẽ khiến mình xem lại lựa chọn:**

> Nếu sau 3 tháng Phase 2, mình thấy debug và đọc paper kỹ thuật nặng tiêu hao năng lượng nhiều hơn là tạo ra — và thấy mình thích hỏi "build cái này để làm gì" hơn là "build cái này như thế nào" — thì đó là tín hiệu nên xem lại về hướng T1.

---

### ⑤ ĐỊNH HƯỚNG & CHUẨN BỊ

**Định hướng tiếp theo:**
- Hoàn thiện RAG project từ Phase 1: thêm evaluation layer (Ragas) → có artifact đo được
- Build thêm 1 project agent end-to-end có real use case (ví dụ: coding assistant, document QA với multi-turn)
- Bắt đầu đọc LangGraph advanced patterns trước Phase 2

**Những thứ cần chuẩn bị:**
- Tạo GitHub portfolio public với README rõ cho 2–3 project Phase 1
- Setup LangSmith account để bắt đầu trace và eval ngay từ đầu Phase 2
- Đọc trước: LangGraph documentation, Ragas docs, một paper về RAG evaluation

**Câu hỏi còn mở:**
- Trong T3, bắt đầu từ fine-tuning hay từ production reliability trước? (Fine-tuning cần GPU — nếu không có thì nên focus reliability và eval trước)
- Multi-agent production-grade khác gì so với những gì mình đã làm ở D9 — Phase 2 sẽ đi sâu đến đâu?
