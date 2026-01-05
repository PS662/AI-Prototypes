# Number Matching

A simple image-based number recognition experiment using pixel matching.

## Overview

This prototype uses basic pixel comparison to recognize handwritten digits:
- Loads example images and converts them to arrays
- Compares test images against stored examples pixel-by-pixel
- Displays match statistics using matplotlib

## Usage

```bash
python number_matching.py
```

The script expects images in the `images/` directory and a training file `numArEx.txt`.
