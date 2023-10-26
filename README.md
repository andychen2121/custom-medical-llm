# custom-medical-llm
Train an LLM to accurately answer questions using data from a selected medical textbook. To be used in a VQA model.

# Instructions
1. Data Ingestion (Optional)
To save the user time, data has already been scraped and collected. Current data is gathered using attached textbook scraper from Mandell's "Core Radiology - 10th Edition." To train on a custom textbook, re-run the textbook scraper and select the relevant PDF when prompted.
2. LLM Creation
Run the Custom LLM file. The stored LLM will be used as the VQA model's text modality.
Currently using a Bigram LLM model as an proof of concept.
3. VQA Creation
(Work in progress) Run the Custom VQA file.
