# NoMercy Tesseract Training Data

This repository contains Tesseract OCR training data files (tessdata) for multiple languages, used internally by NoMercy Entertainment projects.

## Contents

This repository includes:
- **tessdata/** - Directory containing all language training data files (*.traineddata)
- **configs/** - Tesseract configuration files for optimal OCR performance
- **Automated releases** - GitHub Actions workflow for packaging and releasing tessdata

## Languages Supported

The repository includes training data for 100+ languages in the `tessdata/` directory, including but not limited to:
- English (eng)
- Spanish (spa) 
- French (fra)
- German (ger/deu)
- Chinese Simplified (chi_sim)
- Chinese Traditional (chi_tra)
- Japanese (jpn)
- Korean (kor)
- Arabic (ara)
- Russian (rus)
- And many more...

## Usage

### Download Release
1. Go to the [Releases](../../releases) page
2. Download the latest `tesseract-traineddata.tar.gz` file
3. Extract the archive to your Tesseract tessdata directory

### Manual Usage
```bash
# Extract the archive
tar -xzf tesseract-traineddata.tar.gz

# Copy to your Tesseract data directory
cp -r tessdata/* /usr/share/tesseract-ocr/5/tessdata/
```

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Internal Use

This repository is maintained for internal use by NoMercy Entertainment. The training data files are sourced from the official Tesseract project and other compatible sources.