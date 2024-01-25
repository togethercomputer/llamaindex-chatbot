# Open source AI RAG Chatbot

This is a [LlamaIndex](https://www.llamaindex.ai/) and [Together.ai](https://www.together.ai/) RAG chatbot using [Next.js](https://nextjs.org/) bootstrapped with [`create-llama`](https://github.com/run-llama/LlamaIndexTS/tree/main/packages/create-llama).

It's powered by Llama Index, Mixtral (through Together AI Inference) and Together Embeddings. It'll embed the PDF file in `data`, generate embeddings stored locally, then give you a RAG chatbot to ask questions to.

## Getting Started

Copy your `.example.env` file into a `.env` and replace the TOGETHER_API_KEY with your API key from [together.ai](https://www.together.ai).

1. Install the dependencies.

```
npm install
```

2. Generate the embeddings and store them locally in the `cache` folder. You can also provide a PDF in the `data` folder instead of the default one.

```
npm run generate
```

3. Run the app and send messages to your chatbot. It will use context from the embeddings to answer questions.

```
npm run dev
```

## Common Issues

- Ensure your environment file is called `.env`
- Specify a dummy `OPENAI_API_KEY` value in this `.env` to make sure it works (temporary hack, Llama index is patching this)

## Learn More

To learn more about LlamaIndex and Together AI, take a look at the following resources:

- [Together AI Documentation](https://docs.together.ai/docs) - learn about Together.ai (inference, finetuning, embeddings)
- [LlamaIndex Documentation](https://docs.llamaindex.ai) - learn about LlamaIndex (Python features).
- [LlamaIndexTS Documentation](https://ts.llamaindex.ai) - learn about LlamaIndex (Typescript features).
