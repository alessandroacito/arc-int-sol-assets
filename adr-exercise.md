# ADR 001: JMS Queues

## Context

Usage of Queues

## Decision

Decision to use JMS Queues to store the initial load of data from MySQL DB into the queues

## Status

Accepted

## Consequences

The source system MySQL might not be updated on the actual status of the records processed.

## Related documents

[List any related documents, such as requirements or design documents, that influenced the decision.]

### References
- https://github.com/joelparkerhenderson/architecture-decision-record
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/metrics-monitors-alerts/index.md
- https://github.com/pmerson/ADR-template
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/timestamp-format/index.md
- https://cloud.google.com/architecture/architecture-decision-records
