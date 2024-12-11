# Machine-Readable Files (MRF) Analysis Results

Comprehensive analysis of payer MRF endpoints and hosting platforms.

## Coverage Summary
- Total Payers Analyzed: 73
- Successful Analyses: 61
- Payers with Endpoints: 46
- Success Rate: 83.56%

## Hosting Platforms
- **centene**: 6 payers
- **gcp**: 2 payers
- **healthsparq**: 4 payers
- **self_hosted**: 21 payers
- **aws**: 5 payers
- **sapphire**: 6 payers
- **azure**: 1 payers
- **hmhs**: 1 payers

## Endpoint Types
- Index Files: 22
- Other: 39
- Provider References: 6
- Formulary: 4

## File Statistics
- GZip Files: 1
- JSON Files: 100
- Date-based Files: 82

## Repository Structure
- `summary.json`: Overall analysis summary
- `mrf_endpoints.json`: Complete list of identified MRF endpoints
- `platforms/`: Detailed results grouped by hosting platform
- `analytics/`: Additional analytical data and reports

## Analysis Date
2024-12-11T09:26:25.902982

## Notes
- Results include only payers with identified endpoints or documented errors
- Endpoints are deduplicated and categorized by type
- Platform-specific details available in the platforms directory
- File statistics include compression and dating patterns
