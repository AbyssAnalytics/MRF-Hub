# Machine-Readable Files (MRF) Analysis Results

Comprehensive analysis of payer MRF endpoints and hosting platforms.

## Quick Start
- [View All Endpoints](mrf_endpoints.json)
- [Browse by Platform](platforms/)
- [Browse by Payer](payers/)
- [View Analytics](analytics/overview.json)
- [Download Index](index.json)

## Navigation
This repository is organized to make MRF endpoint data easily accessible:

1. **By Platform**: 
   - Find endpoints grouped by hosting platform
   - Each platform has its own JSON file in `platforms/`
   - Currently tracking 9 platforms

2. **By Payer**:
   - Individual payer files in `payers/`
   - Contains endpoints, success rates, and metadata
   - 39 payers with active endpoints

3. **Analytics**:
   - Detailed analysis in `analytics/`
   - Update patterns, common structures, statistics
   - Platform and payer comparisons

4. **Downloads**:
   - Pre-packaged JSON files by platform and payer
   - Compressed archives for bulk download
   - Updated with each analysis

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

## File Structure
- `summary.json`: Overall analysis summary
- `mrf_endpoints.json`: Complete list of identified MRF endpoints
- `platforms/`: Detailed results grouped by hosting platform
- `payers/`: Individual payer results and endpoints
- `analytics/`: Additional analytical data and reports
- `downloads/`: Pre-packaged JSON files by platform and payer

## Analysis Date
2024-12-11T09:26:25.902982

## Notes
- Results include only payers with identified endpoints or documented errors
- Endpoints are deduplicated and categorized by type
- Platform-specific details available in the platforms directory
- Payer-specific details available in the payers directory
