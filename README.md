# Node Quality Check (Composite GitHub Action)

This composite GitHub Action:
- Sets up Node.js
- Installs dependencies
- Runs lint and tests

## Usage

```yaml
- uses: mahekshahbad/composite-actions/node-quality-check@v1
  with:
    node-version: "18"


# Java Quality Check (Composite GitHub Action)

This composite GitHub Action:
- Sets up Java environment
- Builds Maven project
- Runs tests

## Usage

```yaml
- uses: mahekshahbad/composite-actions/java-quality-check@v1
  with:
    java-version: "22"
