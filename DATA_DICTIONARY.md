# Data Dictionary

## `cluster_power.csv`

Per-run power telemetry. Used to compute cluster power distributions and box plots. Cluster power is the summed worker-node power used in the paper analysis.

## `service_state.csv`

Per-service controller/evaluation state over time. Used for threshold-state fractions and profile-distribution figures. Important columns typically include service, intent/threshold bounds, p99 latency or measured latency, profile/node placement, and state such as `below_lower`, `in_band`, or `above_upper`.

## `experiment_run.csv`

Run-level metadata, including scenario, trace scale/level, timestamps, workload, and run identifiers when available.

## `reschedule_events.csv`

Controller actions and placement changes. This is mainly used to understand migration behavior and convergence.

## `power_summary_*.json`

Per-run summary statistics for power measurements.

## `runtime_state_*.json`

Final runtime/controller state captured for the run.

## `intent_config*.yaml`

The intent/threshold configuration used by the controller or evaluation scripts.

