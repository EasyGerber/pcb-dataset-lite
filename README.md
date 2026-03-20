# pcb-dataset-lite

An open collection of PCB designs sourced from open-source projects, normalized for AI training and research.

This is the public subset of a larger dataset used by [EasyGerber](https://easygerber.com) to advance AI-driven PCB design.

## Structure

Each board lives in its own directory under `boards/{owner}/{repo}/{board_name}/`:

```
boards/OLIMEX/ESP32-EVB/ESP32-EVB_Rev_K/
├── board.egb          # Normalized EasyGerber format
├── metadata.json      # Source, license, stats
└── raw/               # Original design files
    └── ESP32-EVB_Rev_K.kicad_pcb
```

## License

This database is licensed under the [Open Data Commons Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/1-0/).

Individual PCB designs retain their original licenses — see each board's `metadata.json` for provenance and license info.
