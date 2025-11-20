# VQ-Bench Dataset Download Instructions

The VQ-Bench dataset is split into multiple parts due to GitHub's file size limits.

## Download

Download all parts from the [Releases page](https://github.com/shreeharsha-bs/Lost-in-phonation/releases):
- `VQ-Bench.zip.partaa` (2.0 GB)
- `VQ-Bench.zip.partab` (522 MB)

## Reassemble the Dataset

### On macOS/Linux:
```bash
cat VQ-Bench.zip.part* > VQ-Bench.zip
unzip VQ-Bench.zip
```

### On Windows (PowerShell):
```powershell
cmd /c copy /b VQ-Bench.zip.partaa+VQ-Bench.zip.partab VQ-Bench.zip
```

Then extract with your preferred zip tool.

## Verify the Download (Optional)

After reassembling, verify the file integrity:
```bash
# The combined file should be approximately 2.5 GB
ls -lh VQ-Bench.zip
```
