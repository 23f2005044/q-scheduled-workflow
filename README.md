# Scheduled Workflow

[![Daily Scheduled Commit](https://github.com/23f2005044/q-scheduled-workflow/actions/workflows/scheduler.yaml/badge.svg)](https://github.com/23f2005044/q-scheduled-workflow/actions/workflows/scheduler.yaml)

A simple repo setup for TDS assignment for scheduled workflow.

## Workflow

The workflow is scheduled to run everyday at 14:30 UTC.

## Trigger

The workflow is triggered by the cron expression `30 14 * * *`. It also has a workflow dispatch trigger to allow manual triggering.