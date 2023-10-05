# Deep Classifier Project

Welcome to the Deep Classifier Project! This repository is built upon the [Deep Learning Project Template](https://github.com/Ashu824/DL_DVC_Template.git), providing a structured foundation for creating and deploying deep learning models for classification tasks. 

## Project Overview

The Deep Classifier Project leverages the template's standardized structure and workflow to simplify the development and deployment of deep learning models. Below, I outline the key steps to get started with this project:

## Project Description
![img](https://github.com/Ashu824/DeepCNNClassifier/blob/main/docs/images/Data%20Ingestion@2x%20(1).png?raw=true)
### Dog Cat Image Classifier

The above project is a simple dog-cat image classifier, serving as a prototype for an end-to-end deep learning project using a standardized structure. It demonstrates the organization, workflow, and components essential for creating a robust deep-learning model for image classification.

### Workflow Overview

1. **Update `config.yaml`**:
   - Define the project's configuration, including artifact storage and folder structure for each pipeline stage.

2. **Update `secrets.yaml` (Optional)**:
   - Store sensitive information or credentials securely in this file if necessary.

3. **Update `params.yaml`**:
   - Configure project-specific parameters, such as training settings, epochs, and train-test ratios.

4. **Update `src` Folder**:
   - a. **config**: Maintain project configurations, including parameters.
   - b. **entity**: Define exact configuration values, ensuring predefined parameters.
   - c. **constants**: Store paths for frequently used entities and configuration files.
   - d. **Utils**: Create utilities for file operations, binary object handling, and JSON report saving.

5. **Update Entity Configuration**:
   - Customize entity configurations to match the project requirements.

6. **Update Configuration Manager in `src/config`**:
   - Modify the configuration manager to handle your project-specific settings.

7. **Update Components**:
   - Configure data ingestion, base model preparation, callbacks, training, and evaluation components as needed.

8. **Update the Pipeline**:
   - Assemble the pipeline by calling the components and defining the stages.

9. **Test Run Pipeline Stage**:
   - Test your pipeline stages to ensure they are working as expected.

10. **Run `tox`**:
    - Use `tox` for testing your package and ensuring compatibility with different environments.

11. **Update `dvc.yaml`**:
    - Create and update the `dvc.yaml` file in the project root for orchestration and connecting pipeline stages.

12. **Run `dvc repro`**:
    - Orchestrate your project using `dvc.yaml` to run all the stages in the pipeline.

13. **Artifacts**:
    - Find all project artifacts, including files and trained models, in the designated artifact storage.

## Getting Started

To get started with the Deep Classifier Project, follow these steps:

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Ashu824/DeepCNNClassifier.git
   ```

2. Follow the workflow steps mentioned above, customizing the project according to your requirements.

3. Collaborate, iterate, and develop your deep learning model with ease, thanks to the structured project organization.

## Acknowledgments

I would like to express my gratitude to the following individuals and organizations for their contributions and inspiration:

- [Ineuron](https://ineuron.ai)

- [SUNNY BHAVEEN CHANDRA (GitHub: c17hawke)](https://github.com/c17hawke)

For their open-source contributions, FSDS course, and for sharing their knowledge on GitHub, which has been a source of inspiration for this project template.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



