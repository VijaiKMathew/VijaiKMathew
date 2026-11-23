<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=10,18,34&height=220&section=header&text=Vijai%20K.%20Mathew&fontSize=42&fontAlignY=38&desc=Staff%20AI%20Engineer%20%7C%20Distributed%20Systems%20%26%20LLMOps%20Architect&descFontSize=18&descAlignY=62&fontColor=ffffff&descColor=60a5fa" width="100%" alt="Vijai K. Mathew Header" />
</p>

<p align="center">
  <a href="https://in.linkedin.com/in/vijaikmathew"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.kaggle.com/vijaikm"><img src="https://img.shields.io/badge/Kaggle-10%20Year%20Veteran-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" /></a>
  <a href="https://huggingface.co/vijaikm"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Location-Bengaluru%2C%20India-EA4335?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Experience-10%2B%20YOE-success?style=for-the-badge&logo=codewars&logoColor=white" alt="Experience" /></a>
</p>

---

### 🌐 Executive Profile & Systems Philosophy

> **Staff AI Systems Engineer & Distributed Architect** specializing in low-latency LLM serving (, ), stateful autonomous agent harnesses (), and enterprise cloud infrastructure (, Databricks CLI

Usage:
  databricks [command]

Databricks Workspace
  fs                                     Filesystem related commands
  git-credentials                        Registers personal access token for Databricks to do operations on behalf of the user.
  repos                                  The Repos API allows users to manage their git repos.
  secrets                                The Secrets API allows you to manage secrets, secret scopes, and access permissions.
  workspace                              The Workspace API allows you to list, import, export, and delete notebooks and folders.

Compute
  cluster-policies                       You can use cluster policies to control users' ability to configure clusters based on a set of rules.
  clusters                               The Clusters API allows you to create, start, edit, list, terminate, and delete clusters.
  global-init-scripts                    The Global Init Scripts API enables Workspace administrators to configure global initialization scripts for their workspace.
  instance-pools                         Instance Pools API are used to create, edit, delete and list instance pools by using ready-to-use cloud instances which reduces a cluster start and auto-scaling times.
  instance-profiles                      The Instance Profiles API allows admins to add, list, and remove instance profiles that users can launch clusters with.
  libraries                              The Libraries API allows you to install and uninstall libraries and get the status of libraries on a cluster.
  policy-compliance-for-clusters         The policy compliance APIs allow you to view and manage the policy compliance status of clusters in your workspace.
  policy-families                        View available policy families.

Workflows
  jobs                                   The Jobs API allows you to create, edit, and delete jobs.
  policy-compliance-for-jobs             The compliance APIs allow you to view and manage the policy compliance status of jobs in your workspace.

Delta Live Tables
  pipelines                              The Delta Live Tables API allows you to create, edit, delete, start, and view details about pipelines.

Machine Learning
  experiments                            Experiments are the primary unit of organization in MLflow; all MLflow runs belong to an experiment.
  model-registry                         Note: This API reference documents APIs for the Workspace Model Registry.

Real-time Serving
  serving-endpoints                      The Serving Endpoints API allows you to create, update, and delete model serving endpoints.

Identity and Access Management
  current-user                           This API allows retrieving information about currently authenticated user or service principal.
  groups                                 Groups simplify identity management, making it easier to assign access to Databricks workspace, data, and other securable objects.
  groups-v2                              Groups simplify identity management, making it easier to assign access to Databricks workspace, data, and other securable objects.
  permissions                            Permissions API are used to create read, write, edit, update and manage access for various users on different objects and endpoints.
  service-principals                     Identities for use with jobs, automated tools, and systems such as scripts, apps, and CI/CD platforms.
  service-principals-v2                  Identities for use with jobs, automated tools, and systems such as scripts, apps, and CI/CD platforms.
  users                                  User identities recognized by Databricks and represented by email addresses.
  users-v2                               User identities recognized by Databricks and represented by email addresses.

Databricks SQL
  alerts                                 The alerts API can be used to perform CRUD operations on alerts.
  alerts-legacy                          The alerts API can be used to perform CRUD operations on alerts.
  alerts-v2                              New version of SQL Alerts.
  dashboards                             In general, there is little need to modify dashboards using the API.
  data-sources                           This API is provided to assist you in making new query objects.
  queries                                The queries API can be used to perform CRUD operations on queries.
  queries-legacy                         These endpoints are used for CRUD operations on query definitions.
  query-history                          A service responsible for storing and retrieving the list of queries run against SQL endpoints and serverless compute.
  warehouses                             A SQL warehouse is a compute resource that lets you run SQL commands on data objects within Databricks SQL.

Unity Catalog
  artifact-allowlists                    In Databricks Runtime 13.3 and above, you can add libraries and init scripts to the allowlist in UC so that users can leverage these artifacts on compute configured with shared access mode.
  catalogs                               A catalog is the first layer of Unity Catalog’s three-level namespace.
  connections                            Connections allow for creating a connection to an external data source.
  credentials                            A credential represents an authentication and authorization mechanism for accessing services on your cloud tenant.
  entity-tag-assignments                 Tags are attributes that include keys and optional values that you can use to organize and categorize entities in Unity Catalog.
  external-lineage                       External Lineage APIs enable defining and managing lineage relationships between Databricks objects and external systems.
  external-locations                     An external location is an object that combines a cloud storage path with a storage credential that authorizes access to the cloud storage path.
  external-metadata                      External Metadata objects enable customers to register and manage metadata about external systems within Unity Catalog.
  functions                              Functions implement User-Defined Functions (UDFs) in Unity Catalog.
  grants                                 In Unity Catalog, data is secure by default.
  metastores                             A metastore is the top-level container of objects in Unity Catalog.
  model-versions                         Databricks provides a hosted version of MLflow Model Registry in Unity Catalog.
  online-tables                          Online tables provide lower latency and higher QPS access to data from Delta tables.
  policies                               Attribute-Based Access Control (ABAC) provides high leverage governance for enforcing compliance policies in Unity Catalog.
  quality-monitors                       A monitor computes and monitors data or model quality metrics for a table over time.
  registered-models                      Databricks provides a hosted version of MLflow Model Registry in Unity Catalog.
  resource-quotas                        Unity Catalog enforces resource quotas on all securable objects, which limits the number of resources that can be created.
  rfa                                    Request for Access enables customers to request access to and manage access request destinations for Unity Catalog securables.
  schemas                                A schema (also called a database) is the second layer of Unity Catalog’s three-level namespace.
  storage-credentials                    A storage credential represents an authentication and authorization mechanism for accessing data stored on your cloud tenant.
  system-schemas                         A system schema is a schema that lives within the system catalog.
  table-constraints                      Primary key and foreign key constraints encode relationships between fields in tables.
  tables                                 A table resides in the third layer of Unity Catalog’s three-level namespace.
  temporary-path-credentials             Temporary Path Credentials refer to short-lived, downscoped credentials used to access external cloud storage locations registered in Databricks.
  temporary-table-credentials            Temporary Table Credentials refer to short-lived, downscoped credentials used to access cloud storage locations where table data is stored in Databricks.
  volumes                                Volumes are a Unity Catalog (UC) capability for accessing, storing, governing, organizing and processing files.
  workspace-bindings                     A securable in Databricks can be configured as __OPEN__ or __ISOLATED__.

Delta Sharing
  providers                              A data provider is an object representing the organization in the real world who shares the data.
  recipient-activation                   The Recipient Activation API is only applicable in the open sharing model where the recipient object has the authentication type of TOKEN.
  recipients                             A recipient is an object you create using :method:recipients/create to represent an organization which you want to allow access shares.
  shares                                 A share is a container instantiated with :method:shares/create.

Settings
  ip-access-lists                        IP Access List enables admins to configure IP access lists.
  notification-destinations              The notification destinations API lets you programmatically manage a workspace's notification destinations.
  settings                               Workspace Settings API allows users to manage settings at the workspace level.
  token-management                       Enables administrators to get all tokens and delete tokens for other users.
  tokens                                 The Token API allows you to create, list, and revoke tokens that can be used to authenticate and access Databricks REST APIs.
  workspace-conf                         This API allows updating known workspace settings for advanced users.

Developer Tools
  bundle                                 Databricks Asset Bundles let you express data/AI/analytics projects as code.
  sync                                   Synchronize a local directory to a workspace directory

Vector Search
  vector-search-endpoints                **Endpoint**: Represents the compute resources to host vector search indexes.
  vector-search-indexes                  **Index**: An efficient representation of your embedding vectors that supports real-time and efficient approximate nearest neighbor (ANN) search queries.

Dashboards
  genie                                  Genie provides a no-code experience for business users, powered by AI/BI.
  lakeview                               These APIs provide specific management operations for Lakeview dashboards.
  lakeview-embedded                      Token-based Lakeview APIs for embedding dashboards in external applications.

Marketplace
  consumer-fulfillments                  Fulfillments are entities that allow consumers to preview installations.
  consumer-installations                 Installations are entities that allow consumers to interact with Databricks Marketplace listings.
  consumer-listings                      Listings are the core entities in the Marketplace.
  consumer-personalization-requests      Personalization Requests allow customers to interact with the individualized Marketplace listing flow.
  consumer-providers                     Providers are the entities that publish listings to the Marketplace.
  provider-exchange-filters              Marketplace exchanges filters curate which groups can access an exchange.
  provider-exchanges                     Marketplace exchanges allow providers to share their listings with a curated set of customers.
  provider-files                         Marketplace offers a set of file APIs for various purposes such as preview notebooks and provider icons.
  provider-listings                      Listings are the core entities in the Marketplace.
  provider-personalization-requests      Personalization requests are an alternate to instantly available listings.
  provider-provider-analytics-dashboards Manage templated analytics solution for providers.
  provider-providers                     Providers are entities that manage assets in Marketplace.

Apps
  apps                                   Apps run directly on a customer’s Databricks instance, integrate with their data, use and extend Databricks services, and enable users to interact through single sign-on.

Clean Rooms
  clean-room-asset-revisions             Clean Room Asset Revisions denote new versions of uploaded assets (e.g.
  clean-room-assets                      Clean room assets are data and code objects — Tables, volumes, and notebooks that are shared with the clean room.
  clean-room-auto-approval-rules         Clean room auto-approval rules automatically create an approval on your behalf when an asset (e.g.
  clean-room-task-runs                   Clean room task runs are the executions of notebooks in a clean room.
  clean-rooms                            A clean room uses Delta Sharing and serverless compute to provide a secure and privacy-protecting environment where multiple parties can work together on sensitive enterprise data without direct access to each other's data.

Database
  database                               Database Instances provide access to a database via REST API or direct SQL.
  psql                                   Connect to the specified Database Instance

Quality Monitor v2
  quality-monitor-v2                     Manage data quality of UC objects (currently support schema).

OAuth
  service-principal-secrets-proxy        These APIs enable administrators to manage service principal secrets at the workspace level.

Identity and Access Management (v2)
  workspace-iam-v2                       These APIs are used to manage identities and the workspace access of these identities in <Databricks>.

Additional Commands:
  account                                Databricks Account Commands
  api                                    Perform Databricks API call
  auth                                   Authentication related commands
  completion                             Generate the autocompletion script for the specified shell
  configure                              Configure authentication
  help                                   Help about any command
  labs                                   Manage Databricks Labs installations
  tag-policies                           The Tag Policy API allows you to manage policies for governed tags in Databricks.
  version                                Retrieve information about the current version of this CLI
  workspace-settings-v2                  APIs to manage workspace level settings.

Flags:
      --debug            enable debug logging
  -h, --help             help for databricks
  -o, --output type      output type: text or json (default text)
  -p, --profile string   ~/.databrickscfg profile
  -t, --target string    bundle target to use (if applicable)
  -v, --version          version for databricks

Use "databricks [command] --help" for more information about a command., ). 10-year Kaggle veteran leveraging competitive benchmarks as an empirical proving ground for zero-leakage cross-validation, high-throughput model execution, and deterministic agent verification.

---

### ⚡ Hallmark Core Competencies

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🚀 Low-Latency LLM Serving & Distributed Inference</h4>
      <ul>
        <li>Distributed model serving with <b>vLLM</b>, <b>TensorRT-LLM</b>, and Triton Inference Server.</li>
        <li>Speculative decoding, continuous batching, chunked prefill, and KV-cache optimization.</li>
        <li>Sub-20ms ITL and sub-60ms TTFT profiling under high concurrency loads.</li>
        <li>Post-training quantization: <b>FP8</b>, <b>AWQ 4-bit</b>, GPTQ, and GGUF distillation.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🤖 Autonomous Multi-Agent Verification Harnesses</h4>
      <ul>
        <li>Cyclic state-machine orchestration and human-in-the-loop guardrails via <b>LangGraph</b>.</li>
        <li>Evidence-gated self-evolving loops: <i>"LLMs propose hypotheses; deterministic components verify them."</i></li>
        <li>Episodic failure memory, transactional rollbacks, and schema regression gates.</li>
        <li>Automated CI/CD evaluation scorecards using <b>DeepEval</b> and <b>Ragas</b>.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>☁️ Enterprise Cloud Native LLMOps & FinOps</h4>
      <ul>
        <li>Containerized microservices on <b>Azure Kubernetes Service (AKS)</b> with <b>HPA</b>.</li>
        <li>Strict FinOps: dynamic cluster hibernation enforcing <b>zero recurring idle cost</b>.</li>
        <li>Distributed training and orchestration on <b>Ray</b> and <b>Databricks</b>.</li>
        <li>Observability pipelines: Prometheus, Grafana, OpenTelemetry, and OpenLLMetry.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🏆 Competitive ML & Mathematical Rigor</h4>
      <ul>
        <li>10-year Kaggle veteran competing in tabular, NLP, and simulation benchmarks.</li>
        <li>Zero-leakage Stratified, Group, and Adversarial Cross-Validation schemes.</li>
        <li>Multi-model ensembling: LightGBM, CatBoost, XGBoost, and DeBERTa/Qwen model soups.</li>
        <li>Vectorized simulation environments in <b>JAX</b> (120,000+ steps/second).</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠️ Production Tech Stack & Tooling

<p align="center">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
  <br>
  <!-- GenAI & Serving -->
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/vLLM-0284C7?style=flat-square&logo=speedtest&logoColor=white" alt="vLLM" />
  <img src="https://img.shields.io/badge/TensorRT--LLM-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="TensorRT" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HuggingFace" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/LlamaIndex-8B5CF6?style=flat-square&logo=semanticweb&logoColor=white" alt="LlamaIndex" />
  <img src="https://img.shields.io/badge/Unsloth-10B981?style=flat-square&logo=lightning&logoColor=white" alt="Unsloth" />
  <br>
  <!-- Cloud & MLOps -->
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks" />
  <img src="https://img.shields.io/badge/Ray-028CF0?style=flat-square&logo=ray&logoColor=white" alt="Ray" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
  <br>
  <!-- Vector & Data -->
  <img src="https://img.shields.io/badge/Qdrant-DC2626?style=flat-square&logo=target&logoColor=white" alt="Qdrant" />
  <img src="https://img.shields.io/badge/Milvus-00A4E4?style=flat-square&logo=buffer&logoColor=white" alt="Milvus" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/ClickHouse-F9D835?style=flat-square&logo=clickhouse&logoColor=black" alt="ClickHouse" />
  <img src="https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=pandas&logoColor=white" alt="Polars" />
</p>

---

### 📌 Featured Production Architectures

| Flagship Repository | Domain & Architecture | Key Production Highlights | Status |
| :--- | :--- | :--- | :---: |
| ✈️ [****](https://github.com/VijaiKMathew/aks-airline-copilot) | **Enterprise LLMOps & FinOps**<br>    | • Containerized on Azure Kubernetes Service (AKS) with HPA<br>• Zero-cost idle posture via FinOps cluster hibernation<br>• C4 Architecture diagrams & ADR-001 through ADR-004 | [![v1.0.0](https://img.shields.io/badge/Release-v1.0.0-blue.svg)](https://github.com/VijaiKMathew/aks-airline-copilot/releases) |
| 🏆 [****](https://github.com/VijaiKMathew/kaggle-s6e10-airline-satisfaction) | **Top 1% Champion Pipeline**<br>   | • Top 1% Gold-Tier ML solution out of 2,400+ international teams<br>• 0.96342 ROC-AUC with leak-free out-of-fold blending<br>• 1-command / replication & live showcase | [![v1.0.0](https://img.shields.io/badge/Release-v1.0.0-gold.svg)](https://github.com/VijaiKMathew/kaggle-s6e10-airline-satisfaction/releases) |
| 🌾 [****](https://github.com/VijaiKMathew/kaggriculture) | **Multi-Agent RL & Simulation**<br>   | • Peak Leaderboard #1 & 3,094 Elo simulation agent<br>• Vectorized environment achieving 120,000+ steps/second<br>• Companion dataset with 510+ downloads on Kaggle | [![v1.0.0](https://img.shields.io/badge/Release-v1.0.0-green.svg)](https://github.com/VijaiKMathew/kaggriculture/releases) |
| 🧠 [****](https://github.com/VijaiKMathew/k12-math-misconception-detection) | **Domain NLP & Model Soups**<br>   | • Automated mathematical misconception diagnosis in student work<br>• Stochastic Weight Averaging & Model-Soup ensembling<br>• Modular training, evaluation, and submission pipeline | [![v1.0.0](https://img.shields.io/badge/Release-v1.0.0-purple.svg)](https://github.com/VijaiKMathew/k12-math-misconception-detection/releases) |
| 🪐 [****](https://github.com/VijaiKMathew/orbit-wars) | **Analytical Geometry & Game AI**<br>   | • Vectorized trajectory rollouts & analytical intercept solvers<br>• Zero-latency game-theoretic decision policies under constraints<br>• Comprehensive visual battle simulator | [![v1.0.0](https://img.shields.io/badge/Release-v1.0.0-orange.svg)](https://github.com/VijaiKMathew/orbit-wars/releases) |
| 🔬 [****](https://github.com/VijaiKMathew/physical-engineerings-last-exam) | **Autonomous Engineering Agents**<br>   | • Autonomous engineering agent verification harness<br>• Deterministic cross-domain physical problem reasoning<br>• Stage 1 writeup & multi-disciplinary solver suites | [![v1.0.0](https://img.shields.io/badge/Release-v1.0.0-red.svg)](https://github.com/VijaiKMathew/physical-engineerings-last-exam/releases) |

---

### 📈 GitHub Analytics & Telemetry

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=VijaiKMathew&show_icons=true&theme=tokyonight&hide_border=true&title_color=60a5fa&icon_color=38bdf8&text_color=94a3b8&bg_color=0d1117" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VijaiKMathew&layout=compact&theme=tokyonight&hide_border=true&title_color=60a5fa&text_color=94a3b8&bg_color=0d1117" alt="Top Languages" height="165" />
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=10,18,34&height=100&section=footer" width="100%" alt="Footer" />
</p>
