# Level 3 - Workflows

This level covers running real, published bioinformatics pipelines with **Nextflow** and **nf-core**, from a small amplicon-sequencing analysis to running that analysis through a job scheduler on an HPC cluster.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/FernandoDuarteF/Bio-informatics-workshops)

Both lessons below are adapted from Eco-Flow's [Nextflow training course](https://github.com/Eco-Flow/training) and included here as reading material.

---

## Workshop Contents

| Part | Lesson | Type | What you'll do |
| :--: | :----- | :--- | :-------------- |
| **1** | [Running an nf-core ampliseq pipeline](./01-Ampliseq/README.md) | Practical | Run a real nf-core/ampliseq analysis on amplicon sequencing data — from raw reads to ASV/taxonomy tables and diversity reports. |
| **2** | [Running a pipeline on an HPC](./02-HPC/README.md) | Practical · optional | Turn a Codespace into a working Slurm cluster, submit and watch jobs by hand, then let Nextflow do the submitting for you. |

---

## Recommended External Resources

- [nf-core/ampliseq documentation](https://nf-co.re/ampliseq)
- [nf-co.re/configs](https://nf-co.re/configs) — ready-made institutional HPC configs
- [Official Nextflow training](https://training.nextflow.io/)

---

## Next Level

If you're looking for more, the original [Eco-Flow training course](https://github.com/Eco-Flow/training) this workshop draws from also covers other pipelines such as differential expression analysis, contributing to pipelines on GitHub, and many other things related to nf-core and Nextflow.
