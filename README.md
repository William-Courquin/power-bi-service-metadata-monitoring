# Power BI Service Metadata Monitoring

## Contents

- project-summary
- problem
- solution
- architecture


## Project Summary

This project monitors Power BI Service metadata, including workspaces, reports, dataflows and refresh activity.

## Problem

There was no easy central view of refresh performance, report inventory or workspace-level metadata.

## Solution

Power Automate collects metadata from the Power BI Service and stores it for reporting. Power BI is then used to visualise refresh trends, failures, workspace activity and report coverage.

## Architecture

Add a short explanation here, then include an image if useful.

![Architecture diagramre.png

## Power Automate Flow

Explain what the flow does:
- Gets workspace details
- Gets dataflow metadata
- Gets report metadata
- Gets refresh history
- Writes results to the chosen storage layer

## Power BI Dashboard

Explain the report pages and what each page shows.

## Screenshots

screenshots/dashboard-overview.png

## Lessons Learned

Summarise what you learned technically and what you would improve next.
