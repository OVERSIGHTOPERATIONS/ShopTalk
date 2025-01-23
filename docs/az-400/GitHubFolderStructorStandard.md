Standard Folder Structure

/project-root
  /docs
    - README.md
    - CONTRIBUTING.md
    - CHANGELOG.md
  /src
    /app
      - main.py
      - requirements.txt
    /tests
      - test_main.py
  /infra
    - main.bicep
    - variables.bicep
  /pipelines
    - azure-pipelines.yml
  /scripts
    - setup.sh
    - deploy.sh
  /config
    - dev.env
    - prod.env
  /.github
    - github-pipelines.yml

Explanation
/docs: Documentation files, including README, contributing guidelines, and changelog.

/src: Source code for your application, organized into subfolders for different components.

/infra: Infrastructure as Code (IaC) files, such as Bicep templates. Contains Infrastructure as Code (IaC) files, such as Bicep templates, ARM templates, or Terraform scripts. These files define the desired state of your infrastructure.

/pipelines: CI/CD pipeline configuration files.

/scripts: Shell scripts for setup, deployment, and other tasks. Contains executable scripts for various tasks, including creating infrastructure components. These scripts can be written in Bash (.sh), PowerShell (.ps1), or Python (.py).

/config: Configuration files for different environments (e.g., development, production).

/.github Github-specific files, such as pipeline definitions.

Tips
Consistency: Keep your folder structure consistent across projects to make it easier for team members to navigate.

Modularity: Organize your code and infrastructure in a modular way to facilitate reuse and maintainability.

Documentation: Include comprehensive documentation to help others understand your project structure and usage.

This structure should help you maintain clarity and efficiency in your Azure DevOps projects.