# Data Collection Policy

## Purpose

This document defines the rules governing the collection of scientific and technical information within the HOLOMED platform.

## Objectives

The data collection process aims to:

- Ensure information quality and reliability.
- Maintain data traceability.
- Avoid duplicate records.
- Standardize collected metadata.

## Approved Sources

The following sources are authorized:

### Scientific Sources

- PubMed
- IEEE Xplore
- Nature
- Springer
- ScienceDirect
- arXiv

### Research Organizations

- Microsoft Research
- NVIDIA Research
- INSERM
- CNRS
- NIH

## Source Management

The approved source list may evolve over time.

### Source Addition Criteria

New sources can be added when they meet the following criteria:

- Proven scientific or institutional reliability.
- Public availability of the data.
- Relevance to HOLOMED domains.
- Compliance with applicable terms of use.

Any addition must:

1. Be documented through a Pull Request.
2. Include a justification.
3. Be approved before integration.
4. Be reflected in the project documentation.

### Source Removal Criteria

A source may be removed when one or more of the following conditions are met:

- The source is no longer available.
- Access restrictions prevent data collection.
- The source repeatedly provides incomplete or unreliable metadata.
- The source is no longer relevant to HOLOMED domains.
- The source violates legal, ethical or licensing requirements.

### Source Removal Procedure

Any source removal must:

1. Be documented through a Pull Request.
2. Include the reason for removal.
3. Assess the impact on existing data collection workflows.
4. Preserve historical records already collected from that source.
5. Be reflected in the project documentation and changelog.

### Traceability

All source additions and removals must remain traceable through the project's Git history.

## Historical Preservation

Removing a source from the approved list does not imply deleting previously collected records.

Previously collected data may be retained for historical, analytical and auditing purposes unless legal obligations require its removal.

## Required Metadata

Each publication must include:

- Title
- Authors
- Publication date
- Source
- URL
- Abstract or description
- Collection date
- Category
- Keywords

## Duplicate Detection

An entry is considered a duplicate when one of the following conditions is met:

- Same DOI
- Same URL
- Identical title
- Similarity score above 95%

Duplicates must not be inserted into the database.

## Traceability

Each collected record must contain:

- Source identifier
- Collection timestamp
- Processing version

## Collection Frequency

Data collection is performed automatically once per week.

Additional job schedules may be introduced as the project evolves.

## Compliance

HOLOMED only stores publicly available metadata and information accessible through authorized sources.