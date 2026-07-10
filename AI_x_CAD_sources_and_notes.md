# AI × CAD — Sources & Notes (companion to deck, July 7, 2026)

Web-sourced research; adversarial verification pass was skipped at user request. Single-source claims are flagged.

## Physna
- Series B $20M, Sequoia (Jan 2021): https://www.prnewswire.com/news-releases/sequoia-leads-20m-series-b-in-physna-an-ohio-based-geometric-deep-learning-startup-301218034.html
- $56M, Tiger Global (Jul 2021): https://www.forbes.com/sites/rashishrivastava/2021/07/01/3d-geometric-search-company-physna-raises-56-million-in-series-b-funding/
- Series A $6.9M (2019): https://www.dcvelocity.com/articles/37901-physna-raises-6-9-million-series-a-funding-to-build-the-google-for-3d
- Patents: https://patents.justia.com/assignee/physna-inc
- Palantir partnership (Dec 6, 2024): https://www.einpresswire.com/article/766612379/
- Shapeways buys majority of Thangs (Dec 18, 2024): https://www.shapeways.com/presscorner/shapeways-acquires-thangs
- DLA / DoD 3D repository: https://www.bmnt.com/blog/3dparts ; https://3dprint.com/305383/
- Gun-blueprint detection (Jun 2026, AP): https://www.ksl.com/article/51510788/ ; EFF criticism: https://www.theregister.com/2026/04/14/eff_california_3dprinted_firearms/
- CEO interview (Apr 2026): https://fifthwavemfg.com/interview-paul-powers-ceo-of-physna/
- Flags: HQ Cincinnati vs Columbus (2026 sources) unconfirmed; revenue $9.8M (GetLatka) unverified; founding year 2015 vs 2016 inconsistent; no disclosed raise since 2021.

## Metafold 3D
- Seed CA$2.35M, Differential Ventures (Jul 2023): https://betakit.com/metafold-3d-closes-2-35-million-cad... ; https://www.finsmes.com/2023/07/metafold-raises-1-78m-in-seed-funding.html
- Pre-seed CA$500K (Aug 2022): BetaKit
- Launch PR (Mar 2021): https://www.globenewswire.com/en/news-release/2021/03/04/2187340
- Docs (implicit kernel): https://docs.metafold3d.com ; SDKs: https://github.com/Metafold3d
- Ross interview (Nov 2024): https://3dheals.com/interview-with-elissa-ross-mathematics-behind-metafold-3d
- Hannover Messe 2026 listing: https://www.hannovermesse.de/exhibitor/metafold/N1569106
- Flags: no post-seed round found; Safran/Ansys/Autodesk/SwRI relationships are logo-wall only; Startuply.vc profile contains hallucinated facts (wrong CEO) — do not trust.

## Siemens IFM
- IFM debut, Hannover Messe (Mar 31, 2025): https://press.siemens.com/global/en/pressrelease/siemens-accelerates-path-toward-ai-driven-industries-through-innovation-and
- IFM technical blog (Aug 2025): https://blogs.sw.siemens.com/nx-manufacturing/teaching-ai-to-speak-the-language-of-engineering-and-manufacturing-through-industrial-foundation-model/
- CES 2026 (NVIDIA "Industrial AI OS", 9 copilots): https://press.siemens.com/global/en/pressrelease/siemens-unveils-technologies-accelerate-industrial-ai-revolution-ces-2026 ; https://nvidianews.nvidia.com/news/siemens-and-nvidia-expand-partnership-industrial-ai-operating-system
- Eigen Engineering Agent (Apr 20, 2026): https://press.siemens.com/global/en/pressrelease/siemens-brings-ai-physical-world-eigen-engineering-agent
- €1B AI investment (Nov 2025): https://press.siemens.com/global/en/pressrelease/siemens-enters-next-stage-growth-its-one-tech-company-program
- 150 PB claim (Bohman, Jun 2025): https://www.automationworld.com/factory/digital-transformation/article/55296419/ — single-origin, not in official PRs
- Analyst context (data fabric): https://www.arcweb.com/blog/industrial-data-fabric-gets-real-siemens-blueprint-ai-scale
- Solid Edge 2026 Design Copilot: https://www.engineering.com/siemens-launches-solid-edge-2026-with-ai-design-copilot/
- Flags: no architecture/benchmark disclosure; whether Eigen runs on IFM unconfirmed; no standalone IFM product or prompt-to-CAD demo as of mid-2026. Note: IFM was announced at Hannover Messe 2025, not CES 2025.

## Mistral AI × CAD
- Physics AI / Emmi (May 2026): https://mistral.ai/news/introducing-physics-ai-at-mistral/ ; https://mistral.ai/news/accelerate-ai-native-industry/ ; https://www.hpcwire.com/aiwire/2026/05/26/mistral-ai-acquires-emmi-ai-to-expand-physics-ai-and-engineering-models/
- Industrial Engineering launch (May 28, 2026 — Airbus, BMW, EDF, CMA CGM): https://www.bloomberg.com/news/articles/2026-05-28/mistral-signs-airbus-and-bmw-as-it-brings-ai-to-manufacturing ; Airbus PR: https://www.airbus.com/en/newsroom/press-releases/2026-05-airbus-partners-with-mistral-ai...
- Manufacturing vertical: https://mistral.ai/industry/manufacturing/
- SOLIDWORKS agents Aura/Marie/Leo on Mistral (Feb 2, 2026): https://develop3d.com/cad/new-solidworks-ai-agents-added-at-3dexperience-world/
- Dassault partnership (Jul 2024 / Nov 2025): https://www.3ds.com/newsroom/press-releases/dassault-systemes-and-mistral-ai-partner-offer-trusted-ai-powered-industry-grade-solutions-accelerate-generative-economy ; https://www.3ds.com/newsroom/press-releases/new-era-sovereign-ai-dassault-systemes-and-mistral-ai-deepen-their-partnership
- ASML €1.3B (Sep 2025): https://www.asml.com/en/news/press-releases/2025/asml-mistral-ai-enter-strategic-partnership ; https://www.cnbc.com/2025/09/09/ai-firm-mistral-valued-at-14-billion-as-asml-takes-major-stake.html
- Stellantis (Feb/Oct 2025): https://www.stellantis.com/en/news/press-releases/2025/october/stellantis-and-mistral-ai-expand-their-collaboration-to-accelerate-enterprise-wide-ai-adoption
- Research: Text-to-CadQuery https://arxiv.org/abs/2505.06507 (Mistral-7B lowest invalid-code rate 1.32%); survey https://arxiv.org/abs/2505.08137 ; note CAD-Recode, BlenderLLM, CADmium use Qwen, not Mistral
- Flags: no Mistral text-to-CAD product; Leo's geometry engine (Mistral vs Dassault AI) unspecified; Emmi ~€300M price single-source; ActuIA: "concrete contracts remain sparse."
