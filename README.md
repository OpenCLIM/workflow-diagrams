# OpenCLIM Workflow Diagrams

Each directory contains an illustration of a workflow created using https://app.diagrams.net

The diagrams are available as PNG images and drawio (XML) files.

Definitions:
- model workflow: A workflow for a single model
- composite workflow: A workflow containing multiple models

# Template
A template file is available in the template directory - https://github.com/OpenCLIM/workflow-diagrams/tree/master/template. This should be copied when creating a new diagram for a workflow.

# Examples
An example set of workflows are available. For individual model workflow examples see:
- https://github.com/OpenCLIM/workflow-diagrams/tree/master/citycat
- https://github.com/OpenCLIM/workflow-diagrams/tree/master/udm

For a composite workflow exmaple see:
- https://github.com/OpenCLIM/workflow-diagrams/tree/master/flood

# Guide
A model workflow diagram should detail the individual datasets and processes required for a lay-person to have an understanding of the inputs required for the model (detailed parameter information not required), the process steps required (model, pre-processing, transformations etc.) and the output datasets.

A composite workflow diagram is intended to highlight in a general manner a set of processes incorporating a number of models which will help answer research questions beyond what a single model might be able to do. The detail of the individual models should be omitted (users can see this in the individual model diagram), but should highlight the transformations and processes that are required to link models together. This could also include decision processes if appropriate.

# Naming Conventions
Directory and file names should be lower case with spaces represented by hyphens.

# FAQ
- Can multiple people modify the same diagram  
No, not at the same time, otherwise this will cause some issues when either of you try to save your edits. Please try and make sure only one person works on a workflow at a time.

- How to save a new workflow  
With draw.io the files are saved directly to GitHub, so you should see a commit option at the top of the screen which allows you to save a message about the changes you have made. These should be specific to your diagram.

