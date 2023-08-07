# Memory Dumps Directory

This folder contains periodic memory dumps stored in two distinct areas. The files are named to reflect their content and the timestamp when they were captured.

## 1. External RAM (`ExtRAM`) Files

- File Size: 512 KB
- Contains data from the periodic dumps of the external RAM area.
- Example: `ExtRAM_20230629143509.bin`

## 2. On-Chip RAM (`OnChipRAM`) Files

- File Size: 128 KB
- Contains data from the periodic dumps of the on-chip RAM area.
- Example: `OnChipRAM_20230629143506.bin`

## Filename Format

Each file's name starts with the representation of the memory area, followed by the timestamp of the dump in the `_YYYYMMDDhhmmss.bin` format:

- `YYYY`: Year
- `MM`: Month
- `DD`: Day
- `hh`: Hour
- `mm`: Minute
- `ss`: Second
