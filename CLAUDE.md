# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a basic Node.js project with Korean language documentation focused on Figma design data extraction and HTML table generation. The project appears to be used for extracting data configuration items and processing logic from Figma designs and inserting them into HTML files as structured tables.

## Commands

### Development
- `node index.js` - Run the main application (outputs "Happy developing ✨")
- `npm test` - Currently not configured (returns error message)

### Project Structure
- `index.js` - Main entry point with basic console output
- `package.json` - Basic Node.js package configuration
- `test1.html` - HTML file containing Korean smart factory enterprise detail tables with data configuration items and processing logic
- `ss.md` - Korean documentation explaining the workflow for extracting Figma design data and generating HTML tables

## Key Workflows

### Figma Data to HTML Table Conversion
Based on `ss.md`, this project is designed to:
1. Extract data configuration items from Figma designs
2. Define processing logic for user interactions
3. Generate HTML tables with specific Korean business data (smart factory enterprise details)
4. Insert these tables into existing HTML files while preserving CSS styles

The HTML structure follows a specific pattern:
- Data configuration table with columns: 항목명 (Item Name), 컨트롤 (Control), 필수 여부 (Required), 수정 가능 여부 (Editable), 설명 (Description), 비고 (Notes)
- Processing logic table with columns: 이벤트명 (Event Name), 입력값/파라미터 (Input/Parameters), 처리내용 (Processing Content), 출력값/처리결과 (Output/Result), 비고 (Notes)

## Language and Context
- Primary language: Korean
- Domain: Smart factory enterprise management system
- Focus: Business process documentation and data structure definition