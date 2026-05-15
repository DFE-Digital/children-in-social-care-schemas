# Child Social Care Data Collection

## Introduction

The Child Social Care (CSC) data collection project aims to improve the collection of social care data from local authorities. It seeks to make the collection and return of aggregated statistics more timely.

The project aims to achieve this by collecting data at a much higher frequency, daily, directly from software suppliers. The data can then be processed through an automated pipeline to generate top-level aggregated measures for presentation on a front-end dashboard.

## Getting Started

Clone the repository.

This is a schema-only project. There is no code to run.

## Build and Test

There is no build or test process.

Once changes are merged into the main branch, the infrastructure team is required to deploy the schema changes to the appropriate environment.

Changes should be tested in lower environments before being moved into Production. Once deployed, update the FAU API documentation as required.

## Contributing

To contribute:

1. Create an appropriate branch.
2. Update the `"version": "x.x.x"` value in `openapi.json`.
3. Use the following version numbering format:

   ```text
   Major.Minor.Patch
   ```

4. Make the required schema changes.
5. Submit a pull request.

Once the pull request is approved, the changes will be merged into the main branch.

After merging, pass the change to the infrastructure team so they can deploy it to the appropriate environment.