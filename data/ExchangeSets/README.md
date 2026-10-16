# Exchange Sets for S-164 Type Approval Testing

These folders contain exchange sets under active development, together with any associated data they require (catalogues, keys, certificates and permits).

Exchange sets are updated frequently as S-164 drafting progresses. Once a milestone is reached, a snapshot of all exchange sets is frozen and bundled — together with the test manual — into an intermediate release posted to the [releases](https://github.com/iho-ohi/S-164-Sub-Group/releases) page.

---

## Folders

### `S-164`

Zipped exchange sets required for S-164 type approval testing, organised by S-164 part. Using this folder avoids the need to search the other folders for individual exchange sets: everything needed to run the S-164 test suite is here, in the correct structure.

| Subfolder | S-164 part |
|---|---|
| `Part2/` | §2 — Data Loading and Management |
| `Part3/` | §3 — Display |
| `Part5/` | §5 — Navigational Hazards |
| `Part6/` | §6 — Special Conditions |
| `Part7/` | §7 — Safety Contour |

### `S-100`

Individual S-100 exchange sets used in S-164 testing. These are the source exchange sets from which the `S-164` folder is assembled. They include S-101 ENCs and all overlay products (S-102, S-104, S-111, S-122, S-124, S-127, S-129, S-131) as well as feature catalogue and catalogue exchange sets.

### `DualFuel`

Exchange sets for dual-fuel ECDIS testing (S-164 §4). These datasets exercise the additional display and alerting requirements for vessels carrying liquefied gas as fuel.

### `S-57`

The original IHO S-57/S-64 test datasets for ECDIS, included here for reference and for S-164 §3 display tests that require the legacy S-57 format. These datasets are identical to the official S-64 test datasets.
