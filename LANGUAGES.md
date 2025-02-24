# Languages

- Python: Great for prototyping and Jupyter Notebooks. However, the lack of type hints in many libraries makes it difficult to use with a LLM.
- TypeScript: 95% of most popular libraries are typed correctly in TypeScript. Of course usually there is the 5% in the libraries that are slightly incorrect and this can be a cause of a lot of pain. `bun --warm` is also great for fast iteration.
- Rust: There is a guarentee that the library is typed correctly. However, when doing things with web APIs that are often by nature less strictly typed, there can be pain points.
