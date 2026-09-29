# Capstone Pitch Deck: Nedbank SmartFin AI Platform

**Emganwini Nedbank Hub | Master Project Portfolio**  
*Phase 6: Final Presentations (Formative Practice)*

---

### Slide 1: Title
- **Title**: Nedbank SmartFin AI Platform
- **Subtitle**: Enterprise-Grade Financial Intelligence & Grounded Generative Copilot
- **Presenter**: Menelisi | Full-Stack Software Engineering Specialization
- **Institution**: Emganwini Nedbank Hub

---

### Slide 2: The Problem
- **Customer Frustration**: Over 68% of retail banking customers find interest rate tiers, notice deposits, and home loan subsidy requirements difficult to parse.
- **Support Bottlenecks**: Call center and branch queues frequently face repetitive informational inquiries.
- **The AI Risk**: Generic LLMs hallucinate non-existent banking terms, fail to comply with the National Credit Act (NCA), and compromise confidential consumer data.

---

### Slide 3: The Solution
- **Nedbank SmartFin AI Platform**: An end-to-end full-stack banking intelligence portal.
- **NedPulse Copilot**: Context-aware conversational banking assistant.
- **Grounded RAG Search**: Vector-based semantic retrieval providing exact product answers backed by official Nedbank citations.
- **3-Sentence Summarizer**: Instant legal disclosure and financial contract distillation.

---

### Slide 4: AI Feature Deep-Dive
- **Architecture**: In-memory dense embeddings + Cosine Similarity Vector Index.
- **Corpus**: 2,500+ words of official Nedbank product documentation chunked into 500-character segments with 50-character overlaps.
- **Strict Grounding**: Zero-hallucination guardrail forcing the assistant to declare unknown queries rather than guessing.
- **Auditability**: Every answer presents clickable source chunk citations with confidence scoring.

---

### Slide 5: Technical System Architecture
- **Frontend**: React 18, Tailwind CSS, Vite, Axios, React Context state management.
- **Backend API**: Node.js, Express.js (ESM), JWT bearer authentication, rate-limiting middleware.
- **Database & Persistence**: PostgreSQL 16 on Neon, Prisma ORM, automated migrations, relational data integrity.
- **Cloud Hosting**: Vercel Edge Network + Render Container Service with SSL encryption.

---

### Slide 6: Live Product Demo & User Flows
1. **User Authentication**: Secure registration and login with bcrypt hashing and JWT issuance.
2. **Advisory Post Hub**: Responsive financial guidance articles with category filters and author permissions.
3. **Conversational Copilot**: Multi-turn dialogue answering queries about notice deposits and tariffs.
4. **Grounded RAG Queries**: Semantic search citing product clauses with sub-150ms retrieval.
5. **Contract Summarization**: 3-sentence executive summaries with token cost transparency.

---

### Slide 7: Business Model & Value Proposition
- **Operational Cost Reduction**: Automated resolution of up to 40% of tier-1 informational inquiries.
- **Deposit Conversion Uplift**: Clearer guidance on notice deposits and wealth instruments accelerates customer capital allocation.
- **Compliance Protection**: Built-in adherence to POPIA and National Credit Act mitigates regulatory liability.
- **B2B Potential**: White-label licensing of the NedPulse copilot to institutional partners.

---

### Slide 8: Future Roadmap
- **Q3 2026**: Multi-lingual conversational support (isiZulu, isiXhosa, Afrikaans, Sesotho).
- **Q4 2026**: OpenBanking API integration for real-time account transaction synchronization.
- **Q1 2027**: WhatsApp Business API Copilot integration for zero-data banking consultation.
- **Q2 2027**: Predictive wealth forecasting and automated portfolio rebalancing.
