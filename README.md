# TaxWise Canada 🍁

AI-powered Canadian tax analyzer for Ontario CRA filings.

## Security
- API key encrypted with AES-256-GCM before storage
- PBKDF2 key derivation (310,000 rounds)
- 5-digit PIN required to access — never stored
- All PDF processing happens locally in your browser
- Nothing is sent to any server except text → Anthropic API

## Usage
Visit the GitHub Pages URL, enter your Anthropic API key and create a PIN.
Your key is encrypted immediately and never stored in plain text.
