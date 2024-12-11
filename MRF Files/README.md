# Machine-Readable Files (MRF) Analysis Results

Comprehensive analysis of payer MRF endpoints and hosting platforms.

## Quick Links
- [View Summary](summary.json)
- [Browse Analytics](analytics/overview.json)
- [Download Index](index.json)
- [View All Endpoints](downloads/manifest.json)

## Repository Structure
This repository is organized to make MRF endpoint data easily accessible:

1. **By Platform** (9 platforms):
   - Find endpoints grouped by hosting platform
   - Complete data: `downloads/platforms/[platform]_complete.json`
   - Endpoints only: `downloads/platforms/[platform]_endpoints.json`
   - Platform list in [index.json](index.json)

2. **By Payer** (39 payers):
   - Individual payer files in `downloads/payers/`
   - Contains endpoints, success rates, and metadata
   - Payer list in [index.json](index.json)

3. **Analytics**:
   - [Overview](analytics/overview.json): patterns, statistics, trends
   - Update frequency and platform comparisons
   - File type analysis and common patterns

4. **Downloads**:
   - [Manifest](downloads/manifest.json): catalog of all available files
   - Pre-packaged JSON files by platform and payer
   - Updated with each analysis run

## Coverage Summary
- Total Payers Analyzed: 73
- Successful Analyses: 61
- Success Rate: 83.56%

## Top Payers
- **Centene**:
  - Endpoints: 102
  - Success Rate: 100.0%
  - Platform: unknown
  - Last Updated: 2024-11-25
- **Ibx**:
  - Endpoints: 15
  - Success Rate: 100.0%
  - Platform: unknown
  - Last Updated: Unknown
- **Amerihealth**:
  - Endpoints: 12
  - Success Rate: 100.0%
  - Platform: unknown
  - Last Updated: Unknown
- **Health1**:
  - Endpoints: 9
  - Success Rate: 100.0%
  - Platform: unknown
  - Last Updated: Unknown
- **Healthy**:
  - Endpoints: 9
  - Success Rate: 100.0%
  - Platform: unknown
  - Last Updated: Unknown
- **Horizonblue**:
  - Endpoints: 8
  - Success Rate: 100.0%
  - Platform: unknown
  - Last Updated: 2024-12-01
- **Bcbsla**:
  - Endpoints: 7
  - Success Rate: 100.0%
  - Platform: unknown
  - Last Updated: 2024-12-01
- **Cigna**:
  - Endpoints: 7
  - Success Rate: 100.0%
  - Platform: unknown
  - Last Updated: Unknown
- **Lifewise**:
  - Endpoints: 7
  - Success Rate: 100.0%
  - Platform: unknown
  - Last Updated: 2024-12-01
- **Premera**:
  - Endpoints: 7
  - Success Rate: 100.0%
  - Platform: unknown
  - Last Updated: 2024-12-01

## Latest Updates
- 2024-12-01: **Bcbskc** updated their endpoints
- 2024-12-01: **Bcbsla** updated their endpoints
- 2024-12-01: **Bci** updated their endpoints
- 2024-12-01: **Horizonblue** updated their endpoints
- 2024-12-01: **Lifewise** updated their endpoints

## Directory Structure

.
+-- index.json                 # Navigation and quick access
+-- summary.json              # Overall analysis summary
+-- analytics/
|   +-- overview.json        # Detailed analytics and patterns
+-- downloads/               # Pre-packaged downloads
    +-- manifest.json        # Download catalog
    +-- platforms/          # Platform packages
    |   +-- centene_complete.json
    |   +-- centene_endpoints.json
    +-- payers/             # Payer packages
        +-- centene.json


## Analysis Date
2024-12-11T09:26:25.902982

## Notes
- Results include only payers with identified endpoints or documented errors
- Endpoints are deduplicated and categorized by type
- Platform-specific details available in the platforms directory
- Payer-specific details available in the payers directory
