# Level 3 - Workflows

This level covers running real, published bioinformatics pipelines with **Nextflow** and **nf-core** — from a small amplicon-sequencing analysis to running that analysis through a job scheduler on an HPC cluster.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/FernandoDuarteF/Bio-informatics-workshops)

> 📦 Both lessons below are adapted from Eco-Flow's [Nextflow training course](https://github.com/Eco-Flow/training) and included here as reading material — see the note at the top of each page for what's runnable as-is versus what needs the original course repo's data/scripts.

## Learning Objectives

After completing this level, you should be able to:

- Explain what nf-core/ampliseq does and what inputs it needs.
- Build a samplesheet and metadata file for an amplicon-sequencing run.
- Run an nf-core pipeline with Docker, and read its results.
- Explain how a cluster (login node, scheduler, compute nodes) differs from a single machine.
- Submit, watch, and cancel jobs on a Slurm/SGE scheduler.
- Configure Nextflow to submit its tasks to a scheduler instead of running them locally.

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

This is currently the last level in this repo's roadmap. If you're looking for more, the [Eco-Flow training course](https://github.com/Eco-Flow/training) this level draws from also covers differential expression analysis, Nanopore metabarcoding, and contributing to pipelines on GitHub.
