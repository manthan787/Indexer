# Indexer
A scalable and efficient file-based Indexer.

This indexer was created as an alternative to Elasticsearch. It is designed to handle large number of documents and terms without using excessive I/O or memory.


The resulting inverted index generated by the indexer is compressed since delta-encoding is used to encode the position of the terms in the termvectors.
