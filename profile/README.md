# Welcome to MONAI :wave:

![project monai](https://github.com/Project-MONAI/.github/blob/main/images/MONAI_Banner.png)

<div align="center">
<a href="http://monai.io">Website</a> | <a href="https://monai.medium.com/">Blog</a> | <a href="https://www.youtube.com/c/Project-MONAI">YouTube</a> | <a href="https://twitter.com/ProjectMONAI">Twitter</a>
</div>

## What is Project MONAI?

Project MONAI is an initiative started initially by NVIDIA and King's College London to establish an inclusive community of AI researchers to develop and exchange best practices for AI in healthcare imaging across academia and enterprise researchers. This collaboration has expanded to include academic and industry leaders throughout the medical imaging field.

Project MONAI has released multiple open-source PyTorch-based frameworks for annotating, building, training, deploying, and optimizing AI workflows in healthcare. These frameworks provide high-quality, user-friendly software that facilitates reproducibility and easy integration. With these tenants, researchers can share their results and build upon each other's work, fostering collaboration among academic and industry researchers.

The suite of libraries, tools, and SDKs within MONAI provide a robust and common foundation that covers the end-to-end medical AI life cycle, from annotation through deployment.

- [MONAI Core](https://github.com/project-monai/monai): A domain-specific framework for training AI models for healthcare imaging
- [MONAI Label](https://github.com/project-monai/monailabel): An intelligent image labeling and learning tool to quickly annotate new datasets
- [MONAI Deploy](https://github.com/project-monai/monai-deploy): Bring trained models from research to clinical deployments.
  - [MONAI Deploy App SDK](https://github.com/project-monai/monai-deploy-app-sdk): Enables developers to take an AI model and turn them into an AI application
- [MONAI Model Zoo](https://github.com/project-monai/model-zoo): A collection of medical imaging models in the MONAI Bundle format

## MONAI Foundational Projects

### MONAI Core

[GitHub](https://github.com/Project-MONAI/MONAI) | [Tutorial](https://github.com/Project-MONAI/tutorials) | [Documentation](https://docs.monai.io/en/stable/)

<details>
  <summary>Learn More</summary>

MONAI Core gives developers and researchers a PyTorch-driven library for deep learning tasks that includes domain-optimized capabilities they need for developing medical imaging training workflows. Performance features such as MONAI Core's AutoML, Smart Caching, GPU accelerated I/O, and image transforms reduce training from days to hours, and hours to minutes, helping users accelerate their AI training pipeline.

</details>

### MONAI Label

[GitHub](https://github.com/project-monai/monailabel) | [Quickstart](https://docs.monai.io/projects/label/en/latest/quickstart.html) | [Documentation](https://docs.monai.io/projects/label/en/latest/index.html)

<details>
  <summary>Learn More</summary>

MONAI Label is an intelligent image labeling and learning tool that uses AI assistance to reduce the time and effort of annotating new datasets. Utilizing user interactions, MONAI Label trains an AI model for a specific task and continuously learns and updates the model as it receives additional annotated images.

MONAI Label has integrations for 3D Slicer, OHIF for Radiology and QuPath, and Digital Slide Archive for Pathology. Developers can also integrate MONAI Label into their custom viewer using server and client APIs, which are well abstracted and documented for seamless integration.

</details>

### MONAI Deploy App SDK

[GitHub](https://github.com/Project-MONAI/monai-deploy-app-sdk) | [Getting Started](https://docs.monai.io/projects/monai-deploy-app-sdk/en/latest/getting_started/index.html) | [Documentation](https://docs.monai.io/projects/monai-deploy-app-sdk/en/latest/index.html)

<details>
  <summary>Learn More</summary>

MONAI Deploy aims to become the de-facto standard for developing packaging, testing, deploying, and running medical AI applications in clinical production. MONAI Deploy creates a set of intermediate steps where researchers and physicians can build confidence in the techniques and approaches used with AI. These steps provide an iterative workflow until the AI inference infrastructure is ready for clinical environments.

MONAI Deploy App SDK enables developers to take an AI model and turn them into AI applications. Available on GitHub, MONAI Deploy is also building open reference implementations of an inference orchestration engine, informatics gateway, and workflow manager to help drive clinical integration.

</details>

### MONAI Model Zoo

[Github](https://github.com/project-monai/model-zoo) | [Models](https://monai.io/model-zoo.html) | [Contribute Your Model](https://github.com/Project-MONAI/model-zoo/blob/dev/CONTRIBUTING.md)

<details>
  <summary>Learn More</summary>

The MONAI Model Zoo is a place for researchers and data scientists to use and share the latest and great models from the community. Utilizing the MONAI Bundle format makes it easy to quickly get started using any model with any MONAI Framework (Core, Label, or Deploy). Or, if you're interested in contributing your models, take a look at our contributing guidelines, which walks you through the process and requirements for submitting your model.

</details>
