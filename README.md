 # Alina de la Noval Armenteros

  **Backend Developer** · MATCOM, Universidad de La Habana · Cáceres, España 🇪🇸

  I build type-safe REST APIs and AI-augmented backends in **C# / .NET, Python and Rust**.
  Currently open to Junior Backend Engineer roles in Spain, Europe and remote.

  ---

  ### Tech Stack

  ![C#](https://img.shields.io/badge/-C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
  ![.NET](https://img.shields.io/badge/-.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
  ![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Rust](https://img.shields.io/badge/-Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
  ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
  ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
  ![Linux](https://img.shields.io/badge/-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
  ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

  **Backend engineering** — ASP.NET Core · Entity Framework Core · FastAPI · Swagger · xUnit · pytest
  **AI & retrieval** — FAISS · sentence-transformers · Ollama · RAG · LSI · scikit-learn
  **Foundations** — Data structures, algorithms, discrete-event simulation, compilers, Monte Carlo

  ---

  ### Currently

  - 🎓 Finishing my BSc in Computer Science at MATCOM — Universidad de La Habana (June 2026)
  - 🦀 Top contributor on the [HULK Compiler](https://github.com/GlenRios/HULK_compiler) — Rust · LLVM · **48 commits**
  - 💼 Open to my first Junior Backend Engineer role
  - 📚 Learning: FastAPI in production, observability, and PostgreSQL at scale

  ---

   ## 💻 Featured Projects

  ### 🦀 [HULK Compiler](https://github.com/GlenRios/HULK_compiler)

  ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
  ![LLVM](https://img.shields.io/badge/-LLVM-262D3A?style=flat-square&logo=llvm&logoColor=white)
  ![Top contributor](https://img.shields.io/badge/Top%20contributor-48%20commits-2bbc8a?style=flat-square)

  **HULK Compiler** is a **full compiler for the HULK programming language** built with **Rust and LLVM** that generates native x86-64 ELF binaries.

  My contribution as **top contributor (48 commits, #1 of 2)**: I built the **entire LLVM IR codegen backend** — type lowering, ObjectRegistry with vtables,
   protocol dispatch via `type_tag` switch, `is`/`as` type checks and `mem2reg` optimization passes. I wrote the **C runtime library** (`hulk_runtime.a`)
  and assembled the **AOT compilation pipeline** with `compile_to_binary`. I also authored the **28-page LaTeX architecture report**.

  This project demonstrates my ability to **build production-grade language backends: LLVM IR emission, ABI design, optimization passes and cross-language
  FFI**.

  📎 [View my commits](https://github.com/GlenRios/HULK_compiler/commits?author=alinadelanoval)

  ---

  ### 🔍 [OmniRetrieve-Engine](https://github.com/fabio2k3/OmniRetrieve-Engine)

  ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
  ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
  ![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
  ![Contributor](https://img.shields.io/badge/Contributor-11%20commits-2bbc8a?style=flat-square)

  **OmniRetrieve-Engine** is a **semantic search + RAG engine over arXiv academic papers** built with **Python, FAISS, LSI and Ollama**.

  My contribution as **contributor (11 commits)**: I built the **LSI retrieval module** — TF-IDF + truncated SVD model with unit and integration tests. I
  designed the **retrieval protocols** enabling protocol-based dense and hybrid retrieval with CrossEncoder reranking. I implemented the **RAG pipeline
  components** (context builder, prompt builder, Ollama generator, end-to-end flow).

  This project demonstrates my ability to **engineer information retrieval systems: model design (LSI over TF-IDF/SVD), protocol-based composition, and
  integration of RAG with local LLMs**.

  📎 [View my commits](https://github.com/fabio2k3/OmniRetrieve-Engine/commits?author=alinadelanoval)

  ---

  ### ⚙️ [Bajas Técnicas — Backend](https://github.com/ABELNoval/BackEnd_IS_and_BD2_Final_Project)

  ![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
  ![.NET](https://img.shields.io/badge/-.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
  ![EF Core](https://img.shields.io/badge/-EF%20Core-512BD4?style=flat-square)
  ![Backend contributor](https://img.shields.io/badge/Backend%20contributor-17%20commits-2bbc8a?style=flat-square)

  **Bajas Técnicas Backend** is a **REST API for equipment lifecycle management** built with **ASP.NET Core 8, Entity Framework Core and xUnit**.
  Domain-Driven Design with role-based access, Swagger docs and PDF reports.

  My contribution as **backend contributor (17 commits)**: I wrote the **entire domain test suite** (12 entity test files + Value Object tests) with
  **Builder-pattern fixtures**. I designed **fluent validators with async repository queries** (uniqueness, existence). I configured **EF Core for DDD**
  with value converters and Table-Per-Type inheritance. I refactored **report generation using CQRS + MediatR + factory pattern**.

  This project demonstrates my ability to **build enterprise C# backends: DDD tactical patterns, Value Objects as sealed records, Builder-pattern test
  fixtures, async validation, and CQRS-based report queries**.

  📎 [View my commits](https://github.com/ABELNoval/BackEnd_IS_and_BD2_Final_Project/commits?author=alinadelanoval)

  ---

  ### 🧭 [Professional Planner](https://github.com/alinadelanoval/professional-planner)

  ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
  ![STRIPS](https://img.shields.io/badge/-STRIPS-blue?style=flat-square)
  ![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
  ![Solo](https://img.shields.io/badge/Solo-275%20tests-2bbc8a?style=flat-square)

  **Professional Planner** is a **career trajectory planner** built with **Python, Ollama and Streamlit** combining **STRIPS classical planning + A\*
  search** with **LLM-as-a-Judge evaluation**.

  As the **sole author**, I modeled career planning as a STRIPS problem with **5 search algorithms** (BFS, A\*, Greedy, Weighted A\* ×2 and ×5). I
  implemented **custom LCG + Box-Muller for Monte Carlo simulation with Common Random Numbers**, integrated Ollama LLM for input parsing and plan
  evaluation, and wrote a **47-page technical report** with the mathematical model.

  This project demonstrates my ability to **design end-to-end AI systems: classical planning, heuristic design, LLM integration with robust fallbacks, and
  stochastic evaluation methodology**. **275 tests · CI on Python 3.10–3.12**.

  📎 [Check the repository](https://github.com/alinadelanoval/professional-planner)

  ---

  ### 📊 [Kojo Kitchen — Discrete Event Simulation](https://github.com/alinadelanoval/kojo-kitchen-des)

  ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
  ![pytest](https://img.shields.io/badge/-pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
  ![LaTeX](https://img.shields.io/badge/-LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
  ![Solo](https://img.shields.io/badge/Solo-44%20tests-2bbc8a?style=flat-square)

  **Kojo Kitchen** is a **discrete event simulation of a fast-food restaurant** built with **Python and pytest** that compares two staffing policies via
  Monte Carlo replications with Common Random Numbers.

  As the **sole author**, I built a discrete event engine with **min-heap Future Event List**, implemented a **custom LCG with Knuth parameters** and
  **independent RNG streams for CRN variance reduction**, and performed **paired t-test analysis** on 30 replications.

  The proposed staffing policy **reduces the unsatisfied customer rate from 16.7 % → 3.1 %** with statistical significance **p = 1.12 × 10⁻¹¹**. Full
  methodology documented in a **47-page LaTeX report** with 7 figures.

  This project demonstrates my ability to **build rigorous stochastic simulations: RNG engineering, event-driven architecture, statistical validation and
  technical reporting**. **44 tests · CI · MIT**.

  📎 [Check the repository](https://github.com/alinadelanoval/kojo-kitchen-des)
  ---

  **Reach me** — alina04.dlna@gmail.com · Cáceres, Spain (CET · UTC+1)
