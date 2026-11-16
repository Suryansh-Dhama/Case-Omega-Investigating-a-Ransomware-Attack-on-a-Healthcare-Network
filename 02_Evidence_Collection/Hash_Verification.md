# Hash Verification Report

## Case Details
- Case Name: Case Omega - Investigating a Ransomware Attack
- Evidence Type: Synthetic demonstration evidence
- Verification Date: 2026-11-16 17:48:49
- Hash Algorithm: SHA-256

## Verification Results

| Evidence File | Original SHA-256 | Working Copy SHA-256 | Match |
|---|---|---|---|
| Login_Records.csv | 9F427CE72E925E7790E065E923DE57B9A1F758B6EFBEEF7BE99D79B2867E384A | 9F427CE72E925E7790E065E923DE57B9A1F758B6EFBEEF7BE99D79B2867E384A | True |
| Ransom_Note.txt | 393903D15499B383F052473A830DC0A84F1099DDC6295084B10D3A7D13C32745 | 393903D15499B383F052473A830DC0A84F1099DDC6295084B10D3A7D13C32745 | True |
| System_Logs.txt | CA2707DE0C12809D5C11CC21817A0955B70D1B2E647E38010E7D71D1C5F9C94A | CA2707DE0C12809D5C11CC21817A0955B70D1B2E647E38010E7D71D1C5F9C94A | True |

## Verification Method
SHA-256 hashes were calculated for each original evidence file and its corresponding working copy using PowerShell's Get-FileHash command.

## Conclusion
All three working copies produced SHA-256 hashes identical to their corresponding original evidence files.

The integrity comparison was successful for all three files at the time of verification.

## Important Limitation
This verification confirms that the working copies match the source files used in this synthetic exercise. It does not independently establish the authenticity, origin, or real-world provenance of the evidence.
