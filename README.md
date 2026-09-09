# Awesome-Simulation-Process-Management

## Top Simulation Process Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Simulation Process & Data Management (SPDM), CAE Workflow Orchestration, HPC Job Management, Design Exploration & Simulation Lifecycle*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Simulation Process Management**. These systems help engineering teams manage simulation data, orchestrate multi-step CAE workflows, submit and monitor jobs on HPC/cloud resources, capture provenance, and support design exploration and optimization.



**Examples** include Rescale, SimScale, Ansys Minerva, Altair One, Nimbix, UberCloud, HEEDS, EnginSoft modeFRONTIER, SimScale Enterprise, and TotalCAE (the category leaders).



**Open-source emphasis**: Full enterprise SPDM platforms with deep CAD/CAE/PLM integration are predominantly commercial. Open-source strength lies in solvers, workflow engines, HPC schedulers, and emerging open SPDM initiatives. **openSPDM**, container-native workflow tools, OpenFOAM ecosystems, and related projects provide useful foundations. This section lists every significant relevant effort found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- |
| **[Rescale](https://rescale.com/)** | Leading cloud HPC and simulation platform that provides intelligent job orchestration, multi-solver support, and scalable infrastructure for CAE workloads. | Starts at $0.05/core-hour on-demand (or $99/month for License Hosting instance) | 5-day free trial with $10–$20 in free compute trial credits |
| **[SimScale](https://www.simscale.com/)** | Browser-based CAE platform offering CFD, FEA, and thermal simulation with collaboration features; enterprise offerings add advanced process and data management. | Starts at $1,500/year (~$125/month) for paid Professional tiers | **Community Plan**: Free forever with 3,000 core-hours/year and 10 active simulations (public projects); 14-day free trial with 500 core-hours |
| **[Ansys Minerva](https://www.ansys.com/products/platform/ansys-minerva)** | Enterprise Simulation Process and Data Management solution (built on Aras technology) for securing simulation data, managing workflows, and integrating with CAD/CAE/PLM tools. | Enterprise license starts at $5,000/year per user seat (or Ansys Elastic Units at $2.00/AEU) | 30-day evaluation trial with 1,000 Ansys Elastic Units (AEUs) upon partner request |
| **[Altair One](https://www.altair.com/altair-one)** | Cloud platform from Altair that unifies access to simulation, HPC, and data analytics tools with process and collaboration capabilities. | Altair Units licensing starts at $50/unit per year (starter pool from $1,500/year) | 30-day free trial on Altair One Marketplace with 50 Altair Units credit; Free Student Edition available |
| **[HEEDS](https://www.siemens.com/)** | Design space exploration and optimization software (now part of Siemens) widely used for automated simulation-driven design studies and process automation. | Commercial subscription starts at $10,000/year per user seat (~$1,200/month) | 30-day evaluation trial license with full solver integration upon request via Siemens partners |
| **[modeFRONTIER (EnginSoft)](https://www.enginsoft.com/software/modefrontier/)** | Process integration and design optimization platform that connects multiple CAE tools into automated, multi-disciplinary workflows. | Commercial license starts at $3,000/year per user seat (~$350/month) | 30-day free trial evaluation license with up to 100 workflow evaluation runs |
| **[Nimbix](https://www.nimbix.net/)** | Cloud HPC platform providing high-performance compute infrastructure, application catalogs, and workload management for engineering simulations. | Compute starts at $0.05/core-hour for CPU instances ($1.50/GPU-hour) | Developer free trial with 20 compute core-hours ($25 trial credit) upon account activation |
| **[UberCloud](https://simr.com/)** | Cloud HPC service provider and container platform offering managed infrastructure, application catalogs, and workload management for engineering simulations. | Starter tier starts at $2,500/year per user seat ($1.00/hour for HPC desktop instances) | 14-day free trial with up to 50 core-hours of containerized HPC simulation testing |
| **[TotalCAE](https://www.totalcae.com/)** | Managed HPC cloud and on-premises simulation platform providing automated web portals and job management for CAE workflows. | Managed service starts at $1,000/month (or BYOC cloud compute at $0.10/core-hour) | 30-day evaluation demo trial with 100 free core-hours of managed cloud simulation |
| **[Other SPDM & simulation platforms](https://rescale.com/)** | Additional commercial solutions from major PLM/CAE vendors (Dassault 3DEXPERIENCE, Hexagon SimManager) providing simulation data management and process automation. | Commercial SPDM licenses start at $3,000–$4,500/year per user seat | 14 to 30-day sandbox evaluation trial with cloud tenant access upon vendor request |



## Open-Source GitHub Projects



- **[openSPDM](https://openspdm.com/)**  

  Open-source Simulation Process and Data Management initiative built on Aras Innovator. Aims to provide a community-driven SPDM platform with connectors to popular CAE tools and solvers.



- **[OpenFOAM](https://www.openfoam.com/)**  

  Leading open-source CFD toolbox. While primarily a solver, its ecosystem includes workflow scripts, case management tools, and community process automation around simulation campaigns.



- **[OpenRadioss](https://github.com/OpenRadioss/OpenRadioss)**  

  Open-source version of the Radioss explicit solver, useful as a building block in broader simulation process pipelines.



- **[Argo Workflows / Kubeflow / scientific workflow engines](https://github.com/argoproj/argo-workflows)**  

  Container-native workflow engines frequently adapted for orchestrating simulation pipelines on Kubernetes and cloud HPC environments.



- **[Nextflow, Snakemake & Cylc](https://github.com/nextflow-io/nextflow)**  

  General scientific workflow systems that many engineering teams adapt for simulation job chains, parameter studies, and reproducible CAE processes.



- **[HPC schedulers & job managers](https://github.com/search?q=SLURM+OR+OpenPBS+OR+HPC+job+scheduler)**  

  Open-source resource managers (Slurm, OpenPBS, etc.) that form the backbone of on-premises and cloud HPC simulation submission.



- **[Salome / code_aster ecosystem](https://www.salome-platform.org/)**  

  Open-source pre/post-processing and FEA platform (EDF) often integrated into custom simulation process chains.



- **[Other CAE automation & scripting frameworks](https://github.com/search?q=CAE+workflow+OR+simulation+automation+OR+SPDM)**  

  Community projects for parameter studies, design of experiments, results harvesting, and lightweight simulation data tracking.



### Additional Strong Open-Source Options



- **Container & environment management**: Apptainer/Singularity, Docker, and environment modules used to make simulation stacks portable.

- **Design of Experiments & optimization libraries**: Open-source tools for parametric studies and surrogate modeling that feed into process management.

- **Data & metadata standards**: Efforts around simulation data formats, provenance capture, and FAIR principles for engineering data.

- **Visualization & post-processing**: ParaView, VisIt, and related open tools commonly embedded in simulation workflows.

- **Python/C++ automation layers**: Scripts and frameworks that wrap commercial or open solvers into repeatable processes.

- Emerging Physics-ML and AI-for-simulation frameworks that integrate with traditional CAE pipelines.



**Frameworks for building custom systems**:  

For open process orchestration, combine **scientific workflow engines** (Nextflow, Snakemake, Argo) with **HPC schedulers** and open solvers (OpenFOAM, OpenRadioss, code_aster).  

**openSPDM** represents one of the few dedicated open efforts toward full Simulation Process & Data Management.  

Enterprise-grade SPDM with deep CAD/PLM integration, audit trails, multi-site collaboration, and vendor-supported connectors remains the domain of commercial platforms (Ansys Minerva, Rescale, Altair One, modeFRONTIER, HEEDS, etc.).  

Many organizations run hybrid environments—open-source workflows and solvers on flexible infrastructure, with commercial SPDM or cloud platforms for governance and scale.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Simulation process and data management systems often sit at the heart of product development and safety-critical decisions. Data integrity, traceability, version control, and intellectual-property protection are essential.

- Open-source tools provide transparency and flexibility but require significant expertise in HPC, CAE, and software engineering to deploy and maintain at production quality. Users remain responsible for validation, security, and compliance of their simulation processes.



---



**Made for CAE engineers, simulation managers, HPC administrators, design exploration specialists, and digital engineering teams.**  

Let's advance open, reproducible, and well-managed simulation processes alongside the powerful commercial SPDM and cloud platforms that industry relies on.
