## A note on the use of the Google Knowledge Graph

(This is only used for the first approach above and just for demonstration purposes.  You can easily substitue any additional data source, including Wikidata.)

We will be working with the Google Knowledge Graph REST API in this example.  Users are permitted 100,000 calls per day for free to the API, but will require an API key for the API calls.  You can read more on how to get this API key [here](https://developers.google.com/knowledge-graph/prereqs).  Once the key is created, it is recommended that you store in in a file named `.api_key` at the root level of this repo.  This should go in the `notebooks/` subdirectory.