# Slurm Cluster Deployment on Chameleon Using Infrastructure Manager (IM)

📌 **NOTE: THIS PROJECT IS A TROVI-COMPATIBLE REPRODUCIBLE EXPERIMENT. RUN THIS NOTEBOOK INSIDE CHAMELEON'S JUPYTERLAB ENVIRONMENT FOR BEST RESULTS.**

This repository provides a simple, fully reproducible experiment that demonstrates how to deploy a **Slurm cluster** on the **Chameleon Cloud** using the [Infrastructure Manager (IM)](https://imdocs.readthedocs.io/en/devel/gstarted.html#im-client-tool), a tool that deploys virtual infrastructures.

### ✅ Reproduce this experiment via: `deploy_slurm_cluster.ipynb`

This experiment:
- Deploys a virtual Slurm cluster in OpenStack on Chameleon using the IM.
- Submits a basic job to the cluster.
- Captures the output of the Slurm job.
- Destroys the infrastructure to free up resources.

---

## ⚙️ Requirements

- A [Chameleon Cloud](https://chameleoncloud.org/) account and access to the KVM@TACC site.

---

## 🚀 Steps in the Notebook

1. **Install the IM client**.
2. **Configure access** to the KVM@TACC OpenStack site.
3. **Deploy infrastructure** using a provided TOSCA recipe.
4. **Run a Slurm job** to demonstrate usage.
5. **Destroy infrastructure** to clean up.

---

## 🔁 Reproducibility and Trovi

This project is designed to work with [Chameleon Trovi](https://chameleoncloud.org/blog/2025/04/21/importing-github-repositories-to-trovi-a-step-by-step-guide/), which allows researchers to:

- Launch Jupyter Notebooks with pre-installed dependencies.
- Avoid authentication hassles — Jupyter is pre-authenticated with Chameleon.
- Easily share artifacts and results with others.
