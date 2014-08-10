SRT Extractor
=============

Alpha-stage project to extract keywords from an SRT subtitle file. Future developments will focus on the extraction of DVB bitmap subtitles from DVB-T/DVB-S broadcasts.

Included in this repo is a sample SRT subtitle file from a BBC 1 DVB-T transmission alongside a simple ruby word-extraction script.

## Future Work

1. Release DVB bitmap subtitle extractor using [Tesseract](https://code.google.com/p/tesseract-ocr/).
2. Develop a command-line interface to output SRT files from a DVB transport stream.

## Usage

`ruby srt_keyword_extract.rb bbc1.srt`
