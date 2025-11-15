# AI JSON Processor & Flowchart Generator

This project demonstrates how to use **Gemini AI** + **Graphviz** inside Google Colab to:

- Transform an input JSON file  
- Generate a professional flowchart describing the transformation  
- Save both the transformed JSON and flowchart image automatically  

## Features

### 1. AI-Based JSON Transformation
Gemini AI performs:
- Combining "first name" + "last name" → "name"
- Prepending `+91` to "phone number"
- Returning clean structured JSON output

### 2. Automatic Flowchart Generation
Gemini produces a **Graphviz DOT diagram**.  
Graphviz converts it into a PNG flowchart.

### 3. Auto-Saved Output Files
The script generates:

- `processed_output.json` — Cleaned JSON returned by Gemini  
- `flowchart_output.png` — Flowchart generated from DOT  

## Project Structure

```
├── sample_input.json
├── processed_output.json
├── flowchart_output.png
├── main.ipynb
└── README.md
```

## Requirements

- Google Colab  
- Gemini API key  
- Internet connection  

## How to Use (Google Colab)

1. Upload `sample_input.json`  
2. Run the Colab notebook by adding required gemini api which can be generated from google AI studio
3. Outputs will be saved automatically  
