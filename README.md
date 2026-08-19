# Power BI Service Metadata Monitoring


## Project Summary

This project uses Power Automate to collect Power BI Service metadata and refresh information, then visualises the results in a Power BI dashboard.

## Problem

There was no single view for monitoring workspace, report, dataflow and refresh metadata across the Power BI Service.

## Solution Overview

Power Automate collects metadata from the Power BI Service and stores it in a structured format. Power BI then connects to that data and provides a monitoring dashboard.

## Architecture

Add your architecture notes or diagram here.

## Power Automate Flow

Explain the flow logic here.

## Data Captured

List the metadata captured, such as workspaces, reports, dataflows and refresh history.

## Power BI Dashboard

Explain the dashboard pages and key visuals.

## Screenshots

Add screenshots here.

## Caveats

### Dataflow - MCode Extraction Function

Supports SharePoint.Files and SharePoint.Contents connectors.

Explicit #"Folder Path" references are treated as the highest-confidence matches.

SharePoint.Contents navigation chains are reconstructed using sequential navigation steps.

Queries using Text.Contains([Folder Path], ...) may not expose the full folder structure.

Dynamically generated paths and parameter-driven URLs cannot always be reconstructed.

The function prioritises accuracy over inference and does not attempt to guess missing folder levels.


## Lessons Learned

Summarise what you learnt.

## Future Improvements

List anything you would add next.
