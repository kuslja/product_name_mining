# The assignment
Create a new model that is able to extract products from Furniture Stores. 

### Inputs
You’ll be given a list of URLs from furnitures stores sites. Most will have products on them, some won’t, some won’t even work at all.

### Outputs

We expect a list of product names extracted from every URL, but you can get creative in presenting your results. See what the most popular product is, aggregate all the pages of a site etc.
Try to showcase what your solution is best at.

### Guidelines

An approach that usually works well with such extraction problems is to create a NER (Named Entity Recognition) model and train it to find your entities (you have one entity, ‘PRODUCT’).

- In order to create such a model you need training data, you can also extract that from the input pages.
- Crawl ~100 pages from the list above & extract the text from it.
- Find a way to tag some sample products from these texts.
- Train a new model from the examples you just made.
- Use it to extract product names from some new, unseen pages.

We recommend using the Transformer architecture from the [sparknlp](https://towardsdatascience.com/named-entity-recognition-ner-with-bert-in-spark-nlp-874df20d1d77) library or the huggingface [transformers](https://medium.com/@andrewmarmon/fine-tuned-named-entity-recognition-with-hugging-face-bert-d51d4cb3d7b5) library.

### Criteria

There are a lot of ways you can showcase your assignment and prove how great it is, but there is a list of criteria which we believe is mandatory and must be present in any great project:

- Explain your though-process, walk us through how the solution works, what else you tried and why you decided to go this route and not others. These explanations help us know you better and help avoid misunderstandings.
- Make your code clear. This is a PoC at most, so it doesn't need to follow production-level code standards. But here, most PoC's turn into production solutions, so make it robust, concise and easy to extend/collaborate.
- Present your outputs clearly. Show how good your solution is using clear metrics, try to convince us this has the potential to be used for real some day.

<aside>
📌 Remember: this is just a rough guideline, please feel free to use any tool or solution you wish, especially if you know it will be better or more interesting!

</aside>
