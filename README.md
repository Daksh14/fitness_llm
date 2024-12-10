# privateGPT

This GPT is fine tuned on the generated embeddings from the text inside the `source_documents` folder

# Environment Setup
In order to set your environment up to run the code here, first install all requirements:

```shell
pip3 install -r requirements.txt
```

Then install the models

Then, download the LLM model and place it in a directory of your choice:

LLM: default to ggml-gpt4all-j-v1.3-groovy.bin. If you prefer a different GPT4All-J compatible model, just download it and reference it in your .env file.

Inside `private-gpt/.env` file update the location of the model

and you should be good to go!


# Query it

Run the server with 

```
deno task server
```

This will spin up a server and you can query the model using the HTTP 

and ask it questions about fitness

# LICENSE

Apache