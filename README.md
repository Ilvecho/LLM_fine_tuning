# FineTuned LLM

This repo covers the whole process we did to generate a fine tuned LLM:
- **Web Scraping**: the notebook contains the code to extract the text from identified URLs. The content extracted from the Web is related to skills needed by HR employees.
- **Docs elaboration**: the notebook contains all the processing steps to go from the raw text extracted from the web to the target format for LoRA fine tuning
- **LoRA_finetuning**: in this notebook it's present the full finetuning pipeline:
    - Creating & loading the dataset
    - Load the base model and run inference with it on the Test set
    - Perform the actual fine tuning
    - Run the tuned model on the Test set
    - Compare the results with the base model

