# Quickstart

This directory contains quickstart examples for using the Anyformat API on Google Cloud.

## Example: Upload a document via cURL

```bash
curl -X POST "https://api.anyformat.cc/v1/documents" \
  -H "Content-Type: application/pdf" \
  --data-binary "@sample-document.pdf"
