# Contributing

For each task, a new branch must be created with a name in the format `feature/<QUEUE_CODE>-<TICKET_NUMBER>`.  
Upon completion of the work on the task, an MR must be created targeting the `main` branch.  
Each MR must:

- have the prefix `<QUEUE_CODE>-<TICKET_NUMBER>` in the title;
- contain a brief description of what was done in form of a todo list;
- pass the pipeline.

After this, it can be sent for review. Before merging into `main`, at least 1 approval is required.

To speed up the review process, verify that your MR contains the following changes:

1. New unit/integration tests for new functionality (or modified class)
2. Updated README (if there were serious changes or additional business functions added)
3. Updated documentation and UML diagrams (if business processes were updated or added)
4. Updated database schemas (if the data model was changed)

It is necessary to remember that code in the main branch can be deployed to prod at any moment. Accordingly, it is necessary to
exclude breaking changes and, if necessary, coordinate MRs across different repositories.
