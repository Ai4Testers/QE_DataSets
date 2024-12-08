# Cross-Browser Compatibility Dataset

This folder contains the **Cross-Browser Compatibility Dataset**, designed to aid Testers and Quality Engineers (QEs) in tasks like retrieval-augmented generation (RAG), fine-tuning, and custom model development.

## **Files in this Dataset**
- `cross_browser_dataset_major_1.0.0.json`  
  The main JSON dataset containing structured data, including:
  - **Synthetic entries** generated exclusively by Ai4Testers.
  - **GitHub-sourced content** from repositories under friendly licenses.
  - **Stack Overflow posts** (with URLs included for attribution, as per CC BY-SA 4.0).
- `json_embeddings_cross_browser_dataset_major_1.0.0.json`  
  Pre-computed JSON embeddings of the dataset for RAG use cases.
- `binary_embeddings_cross_browser_dataset_major_1.0.0.npy`  
  Binary embeddings of the dataset for fine-tuning purposes.

## **Licensing**
- **Synthetic and GitHub-derived data** fall under the **Ai4Testers Public License (APL)**, Version 1.0. For full terms, see [APL License](https://ai4testers.com/licenses/APL-v1.0.txt).
- **Stack Overflow-sourced content** is distributed under the **CC BY-SA 4.0 license**. Attribution is provided within the JSON file via URLs pointing to the original Stack Overflow posts.

## **Attribution**
If you use this dataset, please attribute it as follows:
> This dataset is based on materials provided by Ashwin Palaparthi and Ai4Testers™ ([https://Ai4Testers.com](https://Ai4Testers.com)) under the Ai4Testers Public License (APL).  

For Stack Overflow-sourced content, proper attribution to the original authors is required. Use the URLs included in the JSON file for reference.

## **Author and Organization**
- **Author**: Ashwin Palaparthi  
- **Organization**: Ai4Testers™  
- **Website**: [https://Ai4Testers.com](https://Ai4Testers.com)

## **Disclaimer**
All datasets are provided "as is" without warranty of any kind. Ai4Testers™ assumes no responsibility for any issues arising from their use.
