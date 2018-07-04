# west_logs

This is an attempt to group related log records using [Jaccard similarity coefficient](https://en.wikipedia.org/wiki/Jaccard_index#Generalized_Jaccard_similarity_and_distance).

Inspiration was taken from:
* [Weighted MinHash on GPU helps to find duplicate GitHub repositories](https://blog.sourced.tech/post/minhashcuda/)
* [minhashcuda](https://github.com/src-d/minhashcuda)
* [Locality Sensitive Hashing for semantic similarity](https://github.com/italo-batista/lsh-semantic-similarity/) repository

![Here what has been done so far...](current.png)

What needs to be done in case this attempt will have any kind of future:
* ![Think of a streaning processing, something that might look like](processing_pipeline.png)
* Use [minhashcuda](https://github.com/src-d/minhashcuda) for doing it at scale
