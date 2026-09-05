# Course Notes

## Goal Evaluation

```
                 ┌─────────┐
                 │  GOAL   │
                 └─────────┘
```

### The RAG Triad

```
                    ┌─────────┐
                    │  Query  │
                    └─────────┘
                      ▲     ▲
                     ╱   ↻   ╲
                    ╱         ╲
                   ╱           ╲
        ┌──────────┐  ◄────  ┌──────────┐
        │ Response │         │ Context  │
        └──────────┘         └──────────┘
```

- **Answer Relevance** (Response → Query): Is the response relevant to the query?
- **Context Relevance** (Context → Query): Is the retrieved context relevant to the query?
- **Groundedness** (Context → Response): Is the response supported by the context?
