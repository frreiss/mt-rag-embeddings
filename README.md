# mt-rag-embeddings

This repository contains precomputed embeddings for the data sets in the [MTRAG multi-turn RAG benchmark](https://github.com/IBM/mt-rag-benchmark).

The documents in each data set are split on sentence boundaries into chunks appropriate to the target embedding.

Data is stored in Parquet files with the schema `id, url, title, begin, end, text, embedding`.
