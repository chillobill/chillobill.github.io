
# Automatic documentation challenges:
Time consuming
Low priority
Prone to error
Inconsistent
Difficult to maintain version control
The motivations for automated doc generation
-Standardization

-Consistent look and feel

His solution combines a series of tools, each of which does only one thing. The tools will work together. He suggests two different toolset options:

## 1. Starter Package For Testing:
Markdown
Mermaid
PlantUML
Jinja2
Ansible
Docker
Markdown is included because it’s a simple yet powerful text editor. Mermaid and PlantUML can take text files and turn them into diagrams and charts. Or you can take a Jinja2 template and turni it into a diagram via PlantUML.

## 2. Advanced Package:
Git helps you track changes to your plaintext files, compare changes, create different branches, and commit. Git can be combined with version control systems such as GitHub, GitLab, and others to help you track changes, get change management controls, and integrate with a CI/CD pipeline.
Pandoc is a universal document converter. So for example, you can convert a Markdown file to Word or a PDF.

And LaTeX is purpose-built for technical documents. It includes typesetting features including fonts, spacing, table of contents, alignments, and so on.

# Use Case: Migration Night
You’re running a late-night migration, you’ve been running pre- and post-checks, you have operational commands in files. After the migration, you need to write a document detailing the migration. Why not automate the report?

## The workflow:

-Jinja2 templates

-Graphs

-Ansible as the orchestrator

-Data that comes from third-party systems such as Grafana

-Artifacts
