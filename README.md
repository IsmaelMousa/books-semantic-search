## Books Search Engine With FAISS

Build a search engine using FAISS (Facebook AI Similarity Search) that can help us find the most related book to our quotes or queries, both in English books and Italian.

### Dependencies
- [faiss-gpu](https://pypi.org/project/faiss-gpu)
- [transformers](https://pypi.org/project/transformers)
- [datasets](https://pypi.org/project/datasets)
- [torch](https://pypi.org/project/torch)

```zsh
pip install -r requirements.txt
```
### Datasets
Two datasets that contains a books in two different languages, english and italian.
- [IsmaelMousa/books](https://huggingface.co/datasets/IsmaelMousa/books)
- [IsmaelMousa/libri-in-italiano](https://huggingface.co/datasets/IsmaelMousa/libri-in-italiano)

### Model
A sentence-transformers model that maps sentences  to a 768 dimensional dense vector space and was designed for `semantic search`.

Checkpoint: [sentence-transformers/multi-qa-mpnet-base-dot-v1](https://huggingface.co/sentence-transformers/multi-qa-mpnet-base-dot-v1)

### Languages
- English 🇺🇸
- Italian 🇮🇹

### Results
The performance was so good, the experiment was conducted on a single quote in two different languages, and the resulting books were related very well to the entered quote.
