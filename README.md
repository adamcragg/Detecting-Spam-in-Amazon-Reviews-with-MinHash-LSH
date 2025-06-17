# Detecting-Spam-in-Amazon-Reviews-with-MinHash-LSH


This project identifies duplicate or spammy product reviews using MinHash and Locality Sensitive Hashing.

## 🔧 Tools Used
- Python, NumPy, Dask
- Jupyter Notebook
- Amazon 2023 Reviews Dataset

## 🚀 How to Run
Clone the repo and open the Jupyter notebook. It will automatically download and process the data.

## 📈 Key Concepts
- Shingling
- Jaccard Similarity
- MinHash
- Locality Sensitive Hashing (LSH)

## Results
I was able to find multiple reviews and determine they were highly suspicious. 
Example: Multiple reviews from the same user, with a range of 60-100% Jaccard similarity, all on different products.
True examples are included in the bottom of the jupyter notebook

References:
Dataset - 2023 version
          Bridging Language and Items for Retrieval and Recommendation
          Yupeng Hou, Jiacheng Li, Zhankui He, An Yan, Xiusi Chen, Julian McAuley
          arXiv
          Pdf
          https://amazon-reviews-2023.github.io/.
          

