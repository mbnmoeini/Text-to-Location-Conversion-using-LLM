# Text-to-Location-Conversion-using-LLM
Persian Address Segmentation using LLMs

This project utilizes Large Language Models (LLMs) to segment Persian addresses into meaningful components. It processes addresses using Meta-Llama 3.1-8B via LangChain and the Together API, employing structured prompt engineering to guide the model in extracting address components. The system takes Persian addresses as input and returns a formatted version with properly separated elements.

Additionally, an alternative fine-tuning approach using the Transformers library trains the mt5-small model on Persian address segmentation data. The fine-tuned model is saved for future inference, aiming to improve accuracy through supervised learning.
