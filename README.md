# CAAL – Calculator for Anesthesia and Analgesia in Laboratory Animals

CAAL is a browser-based calculator for planning anesthetic and analgesic substance volumes in laboratory animal experiments.
It is designed to help plan substance volumes before procedures, minimizing dosing errors and reducing substance waste.

## Features

- Anesthesia calculator (ketamine/xylazine and other combinations) — direct and reverse calculation (from dose to volume, or from available volume to dose)
- Atipamezole calculator (for xylazine reversal)
- Analgesia calculator (buprenorphine)
- Calculation history log with filtering and sorting
- Delete individual records from the calculation history
- Backup and restore via JSON export
- Available in Romanian and English
- Each HTML file maintains independent data storage — rename the file after your project (e.g., `Chronic_Analgesia_2026.html`) to keep separate records per project (browser's local storage)

## Disclaimer

Calculations provide guidance on the volumes of substances needed for a given experimental protocol. The author assumes no responsibility for experimental design, substance administration, or outcomes.

## Usage

Two versions are available:

- `CAAL_EN.html` — interface defaults to English
- `CAAL_RO.html` — interface defaults to Romanian

Download the preferred version and open it in any modern browser. No installation or internet connection required. All data is stored locally in the browser (localStorage) and is not transmitted externally. Data can be exported and shared as a JSON backup file.

The file can be renamed after your project. Each uniquely named file maintains its own independent local storage, allowing multiple projects to coexist on the same computer.

The interface language can be switched at any time using the RO/EN toggle in the top-right corner.

A demo file (`CAAL_demo.json`) is available for exploring the application's features. Load it via the **Load back-up** button.

## License

AGPL-3.0-or-later (https://www.gnu.org/licenses/agpl-3.0.html)

## Citation

If you further develop, translate, or adapt CAAL, please give credit to the original:  
https://doi.org/10.5281/zenodo.20829674

## Author

Cristina Ana Mocanu  
Institute of Cellular Biology and Pathology "Nicolae Simionescu", Bucharest

## Acknowledgements

This tool was developed with assistance from Claude (Anthropic).