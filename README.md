# EMD Rack System — Rev 3
**NTPC North Karanpura STPP | 3×660MW | Electrical Maintenance Department**
DGM: Manash Kumar Mitra

## Revision 3 — March 2026
Complete redesign sourced from ALL original NTPC TDS/BOM drawing extracted text files.

### Source Documents Processed
| Drawing No. | Description | Vendor |
|---|---|---|
| 4410-001-102-PVM-Y-017 | 35t Consolidated Hoist | CGL India |
| 4410-001-110-PVM-Y-010 | 15t CEP Under-Slung Crane | Reva / Yaskawa V1000 |
| 4410-001-301B-PVM-W-027 | 15t DG EOT Crane (Intake Well) | Reva |
| 4410-132A-PVM-Y-024 | 10t DG Gantry Crane (Raw Water PH) | Reva |
| 7100139820 | 2t–10t Monorail Hoists | UHF Thane |
| 7100139821 | 17.5t & 20t Under-Hung TWH | UHF Thane |
| 4410-001-110-PVM-B-028 | 2t & 5t Wire Rope Hoists | Century |
| 4410-001-110-PVM-B-122 | 3t Elevator MR Hoist | Mangla |
| 4410-001-110-PVM-Y-250 | BFP Monorail Hoist | Alpha Svcs / Yaskawa A1000 |
| 4410-001-110-PVM-Y-251 | 30t Permanent Store EOT Crane | Alpha Svcs / Yaskawa A1000 |
| 4410-162-PVM-Y-016 | AHP Area: 15t HCSD, 7.5t TAC, 5t Ash, 3t Silo | Reva / LHP |
| NORTH_KARANPURA_7 | UHF Mill Cranes USC-001/002 EH-003/012 | UHF Thane |

### Features
- **55 Motor entries** (BBL / LHP / CGL / ABB / Siemens)
- **69 Brake entries** (DC Disc Pethe/EMCO, AC EHT Electromag, AC EM)
- **100+ Control component entries** (from actual SLD/BOM drawings)
- **36 Auxiliary entries** (rectifiers, drives, DSL, fans, heaters)
- **175 Rack view slots** across 17 crane/hoist types
- **27 Vendor entries** (drawing-referenced)
- **AI Expert** with full site context (Claude Sonnet — requires internet)

### GitHub Pages Setup
1. Upload all 3 files (`index.html`, `.nojekyll`, `README.md`) to repo root
2. Settings → Pages → Source: `main` branch → `/ (root)` → Save
3. Visit: `https://<username>.github.io/<repo-name>/`

### Colour Coding
- **Purple badge (AHP)** — AHP area cranes (4410-162 Reva series)
- **Blue badge (UHF)** — UHF Mill Cranes (Universal Hoist-O-Fabrik)
- **Red badge** — HIGH priority procurement
- **Amber badge** — MEDIUM priority

