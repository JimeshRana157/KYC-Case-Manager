# Sample documents (all fictional)

Plain-text documents you can upload to try each risk rule. No real people or data.

| File | Create the case with name | Expected result |
|---|---|---|
| `valid_id.txt` | Aarav Mehta | Risk 0 (LOW) |
| `expired_id.txt` | Aarav Mehta | DOC_EXPIRED (+30) -> MEDIUM |
| `name_mismatch_id.txt` | Aarav Mehta | NAME_MISMATCH (+25) |
| `sanctions_hit_id.txt` | Rodrigo Valmont Estrada | SANCTIONS_MATCH (+60) + MISSING none -> HIGH |
| `address_proof.txt` | Aarav Mehta | MISSING_FIELDS (+10) (no ID number / DOB on a utility bill) |

You can also upload real PDFs (text-based) or PNG/JPG images (OCR via Tesseract).
