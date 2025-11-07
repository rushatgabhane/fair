# FAIRification of electric vehicle data

## Overview

This repository contains the FAIRified version of the Electric Vehicle Population Data from Washington State (2014 model year). The original dataset from data.gov has been transformed to comply with FAIR (Findable, Accessible, Interoperable, Reusable) principles.

## Dataset

- **Source**: [data.gov](https://data.gov) - Washington State Department of Licensing
- **Scope**: ~3,000 electric vehicle registrations (2014 model year)
- **License**: Open Database License (ODbL)
- **Formats**: CSV, RDF/Turtle

## Repository Contents

- `data.ttl` - FAIRified dataset in RDF format
- `metadata.ttl` - Machine-readable metadata (DCAT)
- `data.csv` - Tabular version of the dataset
- `report.pdf` - Complete FAIRification report
- `.htaccess` - W3ID resolution configuration

## Access

**Persistent Identifier**: `https://w3id.org/FAIR-course-UT/2025-2026/group3/data`

Each vehicle record has a unique URI:  
`https://w3id.org/FAIR-course-UT/2025-2026/group3/data#vehicle_[ID]`

## Vocabularies Used

- **schema.org** - General properties
- **Dublin Core** - Metadata terms
- **DCAT** - Dataset description
- **GeoSPARQL** - Geographic data
- **QUDT** - Units and quantities
- **Custom ev:** - EV-specific concepts
