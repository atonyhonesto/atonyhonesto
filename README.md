<p align="center">
  <img src="assets/banner.svg" alt="Tony Honesto, Cloud & Integration Engineer" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tony-honesto-4195023"><img src="https://img.shields.io/badge/LinkedIn-Tony_Honesto-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/atonyhonesto/tech-articles"><img src="https://img.shields.io/badge/Articles-142_and_counting-6f42c1?style=for-the-badge" alt="Articles"></a>
  <a href="mailto:atonyhonesto@gmail.com"><img src="https://img.shields.io/badge/Email-atonyhonesto@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Based_in-Carmel,_Indiana-0b1f3a?style=for-the-badge" alt="Carmel, Indiana">
</p>

---

### 👋 Hi, I'm Tony

I spend most of my time on the unglamorous, essential part of software: getting data from one system to another **correctly, on time, every time**. That's meant EDI with trading partners, HL7 between hospital systems, BizTalk estates moved onto Azure, and telemetry from a race car to the people making the call on the pit wall.

Lately I'm building the **AI layer on top of that plumbing**: MCP servers in C#, ML pipelines that know when not to trust themselves, and writing about all of it on LinkedIn.

- 🔭 **Building:** .NET 10 MCP servers that let Claude Code query local data in plain English
- ✍️ **Writing:** [142 articles](https://github.com/atonyhonesto/tech-articles) on cloud, integration, data, AI and motorsports tech; 81 of them link to code you can run
- 🏁 **Roots:** timing & scoring at the 2000 Indy 500, NASCAR Race Control, Pi Research data acquisition, Optimum G vehicle dynamics
- 🤝 **Open to:** cloud, integration, data and motorsports/sports-tech engineering roles

---

### ⭐ Featured work

<table>
<tr>
<td width="50%" valign="top">

#### 🏁 [race-speed-inference](https://github.com/atonyhonesto/race-speed-inference)
A pit call has to be on the wall in 25 ms. Per-stage latency budgets, a hard inference timeout, a dual-threshold confidence gate, calibration, drift detection and three-tier fallback, run against a simulated 200-lap race.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![ML](https://img.shields.io/badge/ML_systems-555?style=flat-square) ![Tests](https://img.shields.io/badge/15_tests-2ea44f?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🔌 [ParquetMCPServer](https://github.com/atonyhonesto/ParquetMCPServer)
A Model Context Protocol server in C# that lets Claude Code discover schemas and query local Parquet files from plain-English questions. No SQL, no cloud dependency.

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![.NET 10](https://img.shields.io/badge/.NET_10-512BD4?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-D97757?style=flat-square&logo=anthropic&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🏥 [logicapp-hl7-adt-a01-decoder](https://github.com/atonyhonesto/logicapp-hl7-adt-a01-decoder)
Azure Logic App Standard workflow that decodes HL7 v2 ADT^A01 admissions into validated JSON using the built-in HL7 connector and namespace-agnostic XPath. No hand-rolled parsing.

![Azure](https://img.shields.io/badge/Logic_Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![HL7](https://img.shields.io/badge/HL7_v2-555?style=flat-square) ![Healthcare](https://img.shields.io/badge/Healthcare_IT-555?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🔄 [biztalk-azure-modernization](https://github.com/atonyhonesto/biztalk-azure-modernization)
Case study: moving a logistics company's high-volume EDI platform from on-prem BizTalk to Azure Integration Services. Roadmap, parallel runs, cutover and the team's skills transition.

![BizTalk](https://img.shields.io/badge/BizTalk-555?style=flat-square) ![Azure](https://img.shields.io/badge/Azure_Integration-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![EDI](https://img.shields.io/badge/EDI_X12-555?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧪 [article-labs](https://github.com/atonyhonesto/article-labs)
50 small, runnable apps behind my articles: tire degradation and pit windows, Kafka consumer groups, RAG retrieval, medallion SQL, gRPC, a Java quality gate, WPF MVVM, Terraform. One command each, every lab tested in CI.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![50 labs](https://img.shields.io/badge/50_labs-2ea44f?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🚀 [csharp-fargate-stepfunctions](https://github.com/atonyhonesto/csharp-fargate-stepfunctions)
A C# batch job on AWS Fargate, orchestrated by Step Functions: exit codes decide retry or fail, SIGTERM is handled cleanly, and the state machine is tested offline against the real job code.

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Fargate](https://img.shields.io/badge/Fargate-FF9900?style=flat-square&logo=amazonecs&logoColor=white) ![Step Functions](https://img.shields.io/badge/Step_Functions-E7157B?style=flat-square&logo=amazonaws&logoColor=white)

</td>
</tr>
</table>

<p align="center"><sub>More companion code: <a href="https://github.com/atonyhonesto/edi-x12-mapper">edi-x12-mapper</a> · <a href="https://github.com/atonyhonesto/signalr-vs-sse-dotnet10">signalr-vs-sse-dotnet10</a> · <a href="https://github.com/atonyhonesto/race-data-redis-streams">race-data-redis-streams</a> · <a href="https://github.com/atonyhonesto/oauth2-pkce-jwt-walkthrough">oauth2-pkce-jwt-walkthrough</a> · <a href="https://github.com/atonyhonesto/nodejs-architecture-patterns">nodejs-architecture-patterns</a> · <a href="https://github.com/atonyhonesto/ai-coding-tax-analyzer">ai-coding-tax-analyzer</a> · <a href="https://github.com/atonyhonesto/watch-session-tracker-lightweight">watch-session-tracker</a></sub></p>

<p align="center"><b>📰 <a href="https://github.com/atonyhonesto/tech-articles">tech-articles</a></b>: every LinkedIn article, sorted by theme, with one-page visual deep dives and links to code.</p>

---

### ✍️ Latest on LinkedIn

- 📺 [Three Stakeholders, One Proof of Concept: a real-time watch session tracker](https://www.linkedin.com/pulse/three-stakeholders-one-proof-concept-tony-honesto-rvkqc/) · [code](https://github.com/atonyhonesto/watch-session-tracker-lightweight)
- 👁️ [Agent Reach: Give your AI agent eyes to see the entire internet](https://www.linkedin.com/pulse/agent-reach-give-your-ai-eyes-see-entire-internet-tony-honesto-vemkc/)
- 🐍 [Python Machine Learning in Motorsports](https://www.linkedin.com/pulse/python-machine-learning-motorsports-tony-honesto-aqmmc/) · [code](https://github.com/atonyhonesto/article-labs/tree/main/labs/tire-deg-pit-window)
- ⚡ [AWS Lambda: the fastest code in racing only runs when it has to](https://www.linkedin.com/pulse/aws-lambda-tony-honesto-5risc/) · [code](https://github.com/atonyhonesto/article-labs/tree/main/labs/lambda-race-events)
- 🔌 [A Local C# MCP Server for Parquet Data](https://www.linkedin.com/pulse/local-c-mcp-server-parquet-data-tony-honesto-wu7qf/) · [deep dive](https://github.com/atonyhonesto/tech-articles/blob/main/articles/2026-06-csharp-mcp-server-for-parquet/README.md)

<sub>→ <a href="https://github.com/atonyhonesto/tech-articles">Browse all 142 articles by theme</a> · <a href="https://github.com/atonyhonesto/article-labs">run the code behind them</a></sub>

---

### 🧰 Toolbox

**Languages & frameworks**<br>
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Cloud**<br>
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Logic Apps](https://img.shields.io/badge/Logic_Apps-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)

**Integration & data**<br>
![BizTalk](https://img.shields.io/badge/BizTalk-555?style=flat-square)
![EDI](https://img.shields.io/badge/EDI_X12-555?style=flat-square)
![HL7](https://img.shields.io/badge/HL7-555?style=flat-square)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)

**AI & ML**<br>
![Claude Code](https://img.shields.io/badge/Claude_Code_·_MCP-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_Agents-412991?style=flat-square&logo=openai&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Splunk MLTK](https://img.shields.io/badge/Splunk_MLTK-000000?style=flat-square&logo=splunk&logoColor=white)

---

### 🏁 From the timing stand to the cloud

| Where | What I did there |
|---|---|
| **Cigna** | Cloud Engineering Advisor on Azure; built a Splunk MLTK model that forecast disk exhaustion before it happened |
| **NASCAR** | Competition Technology Operator in Race Control at crown-jewel events |
| **ProTrans International** | Cloud engineer & EDI developer; led the BizTalk → Azure Integration Services migration |
| **Ascension / St. Vincent Health** | Technology engineering lead; BizTalk EDI and Azure Integration Accounts for healthcare |
| **Indianapolis Motor Speedway & Team Green** | Timing & scoring implementation with AMB i.t. for the 2000 Indy 500; IRL consulting |

---

### 📜 Certifications & training

- AWS Knowledge badges: **Events and Workflows** · **Cloud Essentials** · **Serverless** ([Credly](https://www.credly.com/users/tony-honesto))
- OpenAI: **Building Agents**
- Pi Research: **data acquisition**
- Optimum G: **vehicle dynamics**

---

<p align="center"><i>Every lap is a data event. The job is making sure the data gets where it needs to go.</i></p>
