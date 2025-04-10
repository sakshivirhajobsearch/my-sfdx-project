# My SFDX Project

This is a sample Salesforce DX project with the following components:

- Apex Classes
- Lightning Web Components (LWC)
- Apex Triggers
- Scratch Org Definition

## Setup

1. Create a new Scratch Org:

   ```bash
   sfdx force:org:create -f config/project-scratch-def.json -a MyScratchOrg
   ```

2. Push the source to the org:

   ```bash
   sfdx force:source:push
   ```

3. Open the org:
   ```bash
   sfdx force:org:open
   ```
