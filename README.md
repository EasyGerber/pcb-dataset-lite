# pcb-dataset-lite

An open collection of PCB designs sourced from open-source projects, normalized for AI training and research.

This is the public subset of a larger dataset used by [EasyGerber](https://easygerber.com) to advance AI-driven PCB design.

## Structure

```
pcb-dataset-lite/
├── schema/       # Normalized data format specification
├── raw/          # Original design files as-downloaded
├── normalized/   # Processed into unified format
└── metadata/     # Provenance, license, and stats per board
```

## License

This database is licensed under the [Open Data Commons Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/1-0/).

Individual PCB designs retain their original licenses — see `metadata/` for per-board provenance and license info.
