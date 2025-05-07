# FakeNewsNet Web Application - Simplified Setup

This is a simplified package of the FakeNewsNet web application with corrected dependencies and minimal setup requirements.

## Quick Start Guide

1. **Extract this folder** to a location on your computer.

2. **Open a terminal or command prompt** in this folder.

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Start the development server:**
   ```bash
   npm run dev
   ```

5. **Open your browser** and navigate to:
   ```
   http://localhost:3000
   ```

## Troubleshooting

If you encounter any issues:

1. **Make sure you have Node.js installed** (version 16 or higher).

2. **If you get dependency errors**, try installing with the legacy peer deps flag:
   ```bash
   npm install --legacy-peer-deps
   ```

3. **If the application doesn't start**, try clearing npm cache and reinstalling:
   ```bash
   npm cache clean --force
   npm install
   ```

## Features

- **Home Page**: Overview of the FakeNewsNet project
- **Datasets Page**: Browse fake and real news from PolitiFact and GossipCop
- **Analysis Page**: Visual data analysis with charts showing dataset statistics
- **Detection Page**: Tool to analyze news articles for potential fake news
- **About Page**: Detailed information about the project and research

## Project Structure

- `src/app/`: Next.js pages and routes
- `public/dataset/`: FakeNewsNet dataset files

## Original Repository

This web application is based on the [FakeNewsNet repository](https://github.com/KaiDMML/FakeNewsNet.git), which is a data collection tool for fake news research.
