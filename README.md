## Open source AI RAG Chatbot

This is a [LlamaIndex](https://www.llamaindex.ai/) and [Together.ai](https://www.together.ai/) project using [Next.js](https://nextjs.org/) bootstrapped with [`create-llama`](https://github.com/run-llama/LlamaIndexTS/tree/main/packages/create-llama).

It's modified to be powered by Together AI Inference through Mixtral and Together Embeddings.

## Getting Started

Copy your `.example.env` file into a `.env` and replace the TOGETHER_API_KEY with your API key from [together.ai](https://www.together.ai).

1. Install the dependencies:

```
npm install
```

2. Generate the embeddings

```
npm run generate
```

3. Run the app and chat with it

```
npm run dev
```

## Learn More

To learn more about LlamaIndex and Together AI, take a look at the following resources:

- [Together AI Documentation](https://docs.together.ai/docs) - learn about Together.ai (inference, finetuning, embeddings)
- [LlamaIndex Documentation](https://docs.llamaindex.ai) - learn about LlamaIndex (Python features).
- [LlamaIndexTS Documentation](https://ts.llamaindex.ai) - learn about LlamaIndex (Typescript features).
