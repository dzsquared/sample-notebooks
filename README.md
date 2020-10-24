# Sample Jupyter Book with Remote Book Publish Action

This repository is a sample Jupyter book containing a single notebook with a GitHub action to create a remote book for Azure Data Studio.  The workflow is started manually within the GitHub web interface.

## Details of the GitHub Action
Found in the repository .github/workflows folder, the [manual.yml](.github/workflows/manual.yml) file contains the definition of the workflow.  This file can be copied into any GitHub repository and used to create other remote Jupyter books.

### Manual Workflow
The action is manually triggered by navigating to [Actions](../actions), selecting "Manual workflow" from the list of workflows on the left, and clicking the "Run workflow" button that appears on the right.

This will reveal a dialog box requesting the following information:
- directory: Jupyter Book to Release (defaults to whole repository)
- releasename: Release name
- bookname: Book name
- versionnumber: Version number
- languageid: Language id


## Layout of the Sample Jupyter Book
- _data/toc.yml
- content
  - _config.yml
  - README.md
  - SampleNotebook.ipynb