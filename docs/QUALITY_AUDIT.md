# Quality Audit

## Structural Checks

| Check | Result |
|---|---:|
| State/UT records | 36 |
| Columns | 12 |
| Missing populated-table cells | 0 |
| Duplicate state/UT records | 0 |
| Zones | 4 |

## Count Reconciliation

`135,918 + 33,837,859 + 463,530 = 34,437,307`

**Result: PASS**

## Ratio Validation

Active Ratio, Discharge Ratio, and Death Ratio were recalculated from the underlying counts. Differences are within approximately 0.005 percentage points, consistent with two-decimal display rounding.

## Weighted Overall Ratios

- Active: **0.39%**
- Discharge: **98.26%**
- Death: **1.35%**

## Documentation Issues

- Original source URL is not documented in the workbook.
- Collection date is not documented.
- Summing state-level percentages is not an appropriate national rate.
- `Telengana` should be standardized to `Telangana` if the source is being cleaned.
- `Daman and Diu` indicates a historical administrative classification.

## Conclusion

The underlying count data is internally consistent. The main portfolio improvements are provenance, naming consistency, and correct interpretation of aggregate ratios.
