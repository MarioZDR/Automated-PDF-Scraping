Automated PDF Scraping
This repository contains a tool designed for automated PDF scraping from dynamic websites. It leverages web scraping techniques using Playwright to navigate a specified URL, simulating clicks on elements to dynamically load content.

Features:
Dynamic Navigation: Simulates user interactions to load content that is rendered dynamically, ensuring comprehensive data extraction.
PDF Extraction: Identifies and extracts links to PDF files from the dynamically loaded content.
Efficient Downloading: Utilizes Axios to download PDF files seamlessly.
File Organization: Saves downloaded PDFs in a designated folder named "historic," renaming each file based on the date extracted from its URL, ensuring easy identification and management.

How It Works:
Scraping Setup: Specify the target URL from which to scrape PDFs.
Element Interaction: The tool automatically simulates clicks on relevant elements to trigger dynamic content loading.
PDF Link Extraction: Once the content is loaded, it scans for PDF links.
Download Process: Using Axios, the tool downloads the PDFs and saves them in the "historic" folder with names formatted by their respective dates.

Prerequisites:
Node.js
Axios
Playwright