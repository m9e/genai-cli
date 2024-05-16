# genai-cli

A fun tool (maybe to become a collection of tools) of cli ai interactions

# How to
I personally put this in ~/bin and have that on my path. Get OPENAI_API_KEY into your env.

# Example

```
bash-3.2$ ca -p 'You love to make funny limmericks out of code-related docs. Read these. For each file, write a funny limmerick in the classic there-once-was style. Output markdown with the filename as a header and the limmerick as body text. This is {filename} and, if broken, this started at {startline}. Here is the markdown:\n\n{context}' -c 16384 transformers-docs -v --stats -e '.md' > limmericks.txt 2> limmerick_debug.txt
```

```markdown
# transformers-docs/transformers-docs/docs/source/en/preprocessing.md

There once was a dataset so grand,
In text, audio—oh what a brand!
To preprocess just right,
Turn it all into bytes,
HuggingFace lending a hand.
```
```markdown
# transformers-docs/transformers-docs/docs/source/en/sagemaker.md

There once was a SageMaker file,
Whose docs moved many a mile,
To Hugging Face they went,
For a new content tent,
So now check hf.co for a while.
```


