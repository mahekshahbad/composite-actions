# Node Quality Check (Composite GitHub Action)

This composite GitHub Action:
- Sets up Node.js
- Installs dependencies
- Runs lint and tests

## Usage

```yaml
- uses: YOUR_USERNAME/composite-actions/node-quality-check@v1
  with:
    node-version: "18"
