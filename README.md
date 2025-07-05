# Big Bang Number Generator

This script generates an array of numbers from 1 to 100, replacing:
- Numbers divisible by 3 with `BIG`
- Numbers divisible by 5 with `BANG`
- Numbers divisible by both 3 and 5 with `BIGBANG`

The result is saved to `output.json`.

## Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [TypeScript](https://www.typescriptlang.org/)

## Setup Instructions

1. **Install dependencies** (if you don't have TypeScript globally):
   ```bash
   npm install -g typescript
   ```

2. **Run the script:**
   ```bash
   tsc bigbang.ts
   node bigbang.js
   ```
   This will generate `output.json` in the same directory.

## Output
The `output.json` file will contain an array like:
```
["1", "2", "BIG", "4", "BANG", "BIG", ...]
``` 