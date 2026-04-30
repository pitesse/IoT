# Challenge 3 - Delivery Notes

Generated artifacts are in this folder.

## Core deliverables
- `Challenge.pdf`
- `Exercise.pdf`
- `nodered.txt`
- `id_log.csv`
- `filtered_elems.csv`
- `outgoing_cost.csv`

## Extra helper files
- `FORM_VALUES.txt` (copy/paste values for the online form)
- `thingspeak_queue.csv` (ordered outgoing costs to send to ThingSpeak, 20s pacing)
- `run_summary.json` (run metadata)
- `PERSONCODE1_PERSONCODE2.zip` (submission template archive)

## Important placeholders to update before final upload
- Team names and person codes in `Challenge.pdf` and `Exercise.pdf`
- ThingSpeak public channel URL in `Challenge.pdf` and `FORM_VALUES.txt`
- ZIP filename to your real person codes

## Regeneration scripts
- `generate_challenge3_outputs.py` -> regenerates CSV outputs from 200-message simulation
- `build_nodered_flow.py` -> regenerates `nodered.txt`
- `build_reports.py` -> regenerates PDFs and form helper
