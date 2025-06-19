# GitHubStar_Nomination
## Contact Information
- X: @YoutanDml (https://x.com/YoutanDml)
- LinkedIn: https://www.linkedin.com/in/yutaka-osada0922/
- Zenn (my techblogs): https://zenn.dev/yutakaosada
- GitHub: https://github.com/yutaka-art

## SpeakerDeck (archive of my slides)
https://speakerdeck.com/yutakaosada

## Why do you want to be a GitHub Star?
I want to become a GitHub Star because my professional mission is to turn complex DevOps theory into practical, repeatable workflows that any team can adopt.
As a DevOps Engineer and community speaker in Japan, I specialise in Infrastructure as Code, multi-stage CI/CD pipelines, and secure developer platforms on GitHub and Azure. Over the past year I have:

- Spoken at flagship conferences – DevOps Days Tokyo 2025, GitHub Dockyard, Microsoft Build recaps – to share live demos of GitHub Copilot, Advanced Security, and GitHub Actions runner patterns on Azure.
- Authored deep-dive technical content – a forthcoming AZ-400 book chapter on IaC, step-by-step Zenn articles on self-hosted runners, Copilot metrics.
- Mentored engineers through hands-on workshops that migrate legacy pipelines to GitHub while codifying governance policies and threat-modeling with IaC.
- Advocated for Workload Identity & OIDC to eliminate long-lived secrets, helping enterprises adopt safer authentication in minutes.

Becoming a GitHub Star would amplify these initiatives, giving me direct feedback loops with the GitHub product team and a global network of Stars. Together we can accelerate best-practice adoption for IaC and pipeline automation, raise the bar for developer experience in regulated industries, and inspire the next wave of open-source contributors in Japan and beyond.

## Records of my accomplishments over the past 12 months

### Speaking Contributions
1. Speaker at DevOps Days Tokyo 2025 – “Fortifying Enterprise Security with GitHub Audit Logs & Azure-Based Analytics Platform”

- Date: April 15, 2025
- Link: https://confengine.com/conferences/devopsdays-tokyo-2025/proposal/21874/github
- Description
  - Delivered an **accepted advanced-level talk** (20 mins, Hall A) selected through a highly competitive CFP process at DevOps Days Tokyo 2025 – Japan’s premier DevOps conference.
  - Attracted 18 “Interested” registrations on ConfEngine, placing the session in the top quartile of the Administration & Security track.
  - Showcased a cross-community solution that streams GitHub Enterprise audit logs into Azure Event Hubs and Cosmos DB for real-time anomaly detection and compliance reporting, while also analysing GitHub Copilot telemetry.
  - Shared IaC samples (Bicep), Dapr/KEDA patterns, and rate-limit-aware GitHub API strategies, highlighting practical DevSecOps governance in the generative-AI era.
- Slide link: https://speakerdeck.com/yutakaosada/202504xx-githubjian-cha-roguwohuo-yong-sitaentapuraizuxiang-kesekiyuriteiqiang-hua-todetafen-xi-ji-pan-nogou-zhu
- YouTube: https://www.youtube.com/watch?v=TpEmCG57fQQ

2. Speaker at GitHub Dockyard – “GitHub Audit Logs × Cloud Analytics for Enterprise-grade Security”

- Date: February 25, 2025  
- Link: https://github-dockyard.connpass.com/event/345814/
- Description  
  - Delivered a 30-minute technical session at **GitHub Dockyard**, a Japan-based community event focused on advanced GitHub use cases. The talk was accepted through a CFP process and positioned as the security highlight of the day.
  - Demonstrated a reference architecture that streams GitHub Enterprise audit logs into **Azure Event Hubs**, processes them with **Azure Functions**, and stores enriched data in **Cosmos DB** and **Log Analytics** for near-real-time threat detection and compliance reporting.
  - Shared Infrastructure-as-Code (Bicep) templates, Function-app code, and GitHub REST-API scripts, enabling attendees to reproduce the solution in their own environments.
  - Emphasised best practices for secure token management (GitHub Apps Installation Tokens vs. PATs), rate-limit-aware data collection, and integration with GitHub Copilot telemetry to correlate code activity with security insights.
- Slide link: https://speakerdeck.com/yutakaosada/20250225-githubjian-cha-roguxkuraudofen-xi-deshi-xian-suruentapuraizusekiyuriteiqiang-hua
- YouTube: https://www.youtube.com/live/V020w8w8MwI?si=taSLNhnHIGNPh1hp

### Blog post contributions
1. Blog Post – “Unpacking GitHub Copilot’s New Premium Models & Request Quotas”

- Date: June 19, 2025
- Link: https://zenn.dev/yutakaosada/articles/5f607ed5b03205
- Description
  - Clarifies the two model categories (Base vs. Premium) and explains how monthly Premium Request allocations (300 for Business, 1,000 for Enterprise) are consumed, including per-model multipliers (e.g., GPT-4.5 = ×50).
  - Details overage pricing ($0.04 USD per request), shows how to set spend caps via **Budgets & Alerts**, and walks readers through exporting Premium Request usage reports from the GitHub UI.
  - Includes original comparison tables, YAML front-matter, screen captures, and VS Code tips so both administrators and individual developers can monitor consumption in real time.
  - Article quickly circulated on Zenn and social media, helping enterprises forecast Copilot costs and avoid unexpected charges while adopting AI-assisted development at scale.

2. Blog Post – “Automating GitHub Organization Audit Log Export to Azure Blob Storage”

- Date: January 15, 2025
- Link: https://zenn.dev/yutakaosada/articles/84b66b2ba6d282
- Description
  - Explains why GitHub audit logs are only retained for 90 days by default and outlines the need for long-term external storage to meet enterprise security and compliance requirements.
  - Provides an end-to-end C# example (.NET 8) that calls `GET /orgs/{org}/audit-log` with a PAT, handles SAML SSO token authorization, and uploads the JSON output to Azure Blob Storage via the **Azure.Storage.Blobs** SDK.
  - Details the required PAT scopes (`audit_log`, `admin:org`), shows how to set the **User-Agent** header, and describes paging strategies for large log sets while respecting GitHub API rate limits.
  - Includes original code listings, JSON samples, screenshots, and step-by-step instructions so DevOps teams can operationalize continuous audit-log offload and cloud-based analysis in minutes.

3. Blog Post – “Building GitHub Actions Self-Hosted Runners on Azure Container Apps (GitHub App Authentication)”

- Date: December 20, 2024
- Link: https://zenn.dev/yutakaosada/articles/6ce1577a84db2d
- Description
  - Walks readers through creating a **self-hosted GitHub Actions runner cluster on Azure Container Apps**, using GitHub App authentication instead of PATs for long-lived, scalable CI/CD workloads.
  - Provides step-by-step Azure CLI scripts that set up ACR, ACA, Key Vault, Managed Identity, and a KEDA scaler; includes environment-variable templates and ARM/CLI one-liners to help teams reproduce the environment quickly.
  - Shows how to fork Microsoft’s sample runner image, modify `entrypoint.sh` to generate a JWT, exchange it for an installation access token, and register the runner dynamically—with full Bash source code.
  - Emphasizes security best practices (Key Vault-backed secrets, Managed Identity, GitHub App short-lived tokens) and demonstrates auto-scaling runners based on queue length, reducing cost while preserving performance.

4. Blog Post – “Building GitHub Actions Self-Hosted Runners on Azure Container Apps (PAT Authentication)”

- Date: December 17, 2024
- Link: https://zenn.dev/yutakaosada/articles/f150d9d403656a
- Description
  - Step-by-step guide that converts Microsoft’s official sample into a **production-ready workflow** for running self-hosted runners on Azure Container Apps using a Personal Access Token (PAT).
  - Supplies ready-to-run Azure CLI snippets that provision ACR, ACA, Log Analytics, and the KEDA GitHub-runner scaler, then deploy a container image that registers runners automatically via PAT.
  - Highlights PAT security best practices—minimal scopes, periodic rotation, and secret-ref injection—ensuring runners authenticate safely without hard-coding credentials.
  - Demonstrates how to edit workflow YAML (`runs-on: self-hosted`) and verify scaling with `az containerapp job execution list`, giving DevOps teams a template for **cost-efficient, scalable CI/CD** in custom environments.


5. Blog Post – “Deploying Azure Resources as IaC with GitHub Actions & Bicep”

- Date: November 8, 2024
- Link: https://zenn.dev/yutakaosada/articles/a5d77da31ce26d
- Description
  - Explains how to deploy Bicep files to Azure from **GitHub Actions**, comparing two credential patterns: classic **Service Principal** login vs. modern **OIDC / Workload Identity**.
  - Walks through creating an Entra ID application, setting up federated credentials, and mapping its IDs to `AZURE_CLIENT_ID`, `AZURE_TENANT_ID`, and `AZURE_SUBSCRIPTION_ID` secrets in the repository.
  - Provides a full OIDC-based sample workflow that logs in with `azure/login@v1`, then deploys `main.bicep` via `azure/arm-deploy@v1`, complete with `workflow_dispatch` inputs and permission scopes.
  - Highlights the operational difference from **Azure DevOps Service Connections**: with GitHub Actions there is no built-in “connection test,” so it proposes a tiny login workflow to validate tokens before production runs.
  - Includes CLI snippets for provisioning ACR, ACA, and other Azure components, plus the full source code in the public repo <https://github.com/yutaka-art/bicep_deployment>.

6. Blog Post – “Deploying GitHub Copilot Metrics Viewer to Azure Static Web Apps”

- Date: September 3, 2024
- Link: https://zenn.dev/yutakaosada/articles/018772bd0ce461
- Description
  - Shows how to fork the **Copilot Metrics Viewer** project, test it locally with mocked data, and then deploy it to **Azure Static Web Apps** through a GitHub Actions pipeline.  
  - Walks readers through creating a PAT with `copilot`, `manage_billing:*`, `read:enterprise`, and `read:org` scopes; mapping it to `VUE_APP_GITHUB_TOKEN`; and exposing runtime settings (`VUE_APP_SCOPE`, `VUE_APP_GITHUB_ORG/ENT`, `NODE_ENV`) via repository **Secrets & Variables**.  
  - Details the Static Web Apps wizard (Standard plan for basic auth), highlights the auto-generated workflow, and explains the additional `env:` block needed to pass secrets to the build step.  
  - Provides screenshots of each Metrics Viewer dashboard (Acceptance Rate, Total Suggestions/Acceptances, Language Breakdown, Copilot Chat, Seat Analytics) and explains how teams can track adoption, active users, and ROI (target acceptance ≈ 30%).  
  - Concludes with best-practice tips for secure token handling, using mocked data in dev (`VUE_APP_MOCKED_DATA=true`), and extending the solution with other Azure services.

### OSS Project Contribution
1. Azure Durable Functions Worker Example for Zenn Article
- Date: January 22, 2025
- Link: https://github.com/yutaka-art/DurableFunction_Worker
- Description
I developed a sample C# project demonstrating the use of Azure Durable Functions, created to accompany a Zenn technical article. This repository provides practical examples for implementing reliable, scalable workflows on Azure using Durable Functions, helping developers understand stateful orchestration patterns in serverless architectures. It serves as a helpful resource for anyone looking to get started with or deepen their knowledge of Azure Durable Functions.

2. Application Insights Worker Utility
- Date: September 30, 2024
- Link: https://github.com/yutaka-art/ApplicationInsights_Worker
- Description
I created a C# utility project designed to work with Azure Application Insights. This worker helps automate the collection, processing, or analysis of telemetry data, making it easier for developers and DevOps teams to monitor application performance. By leveraging this tool, teams can gain deeper insights into their application's health and quickly address issues, contributing to more reliable and efficient cloud-based solutions.

3. Swagger YAML File Merge Tool
- Date: September 16, 2024
- Link: https://github.com/yutaka-art/swagger-detect-merger
- Description
I developed a tool for merging multiple `swagger.yaml` files, streamlining the integration process for API documentation maintained across different sources. This utility helps teams consolidate Swagger/OpenAPI definitions, reducing manual effort and minimizing errors when combining specifications. It is particularly useful for large projects or organizations managing several microservices, ensuring unified and up-to-date API documentation.
