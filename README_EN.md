# ChatGPT Prompt Engineering for Developers -- Course Notes

Course by Andrew Ng and Isa Fulford.

These are structured notes from the course *ChatGPT Prompt Engineering
for Developers*.

## Key Topics

-   Prompt engineering principles
-   Iterative prompt development
-   Summarizing
-   Inferring
-   Text transformation
-   Text expansion
-   Chatbot development

## Core Principles

1.  Write clear and specific instructions
2.  Give the model time to think

## Prompt Engineering Techniques

### Delimiters

Use markers such as triple quotes to separate instructions from input
text.

### Structured Output

Ask the model to return JSON, HTML or tables.

### Few-shot prompting

Provide examples of desired outputs.

### Chain-of-thought reasoning

Encourage step-by-step reasoning.

### Reduce hallucinations

Ask the model to quote relevant text before answering.

## Iterative Development

Prompt engineering is an iterative cycle:

1.  Idea
2.  Test
3.  Evaluate
4.  Improve

## Temperature Parameter

Temperature controls creativity.

-   Temperature = 0 → deterministic
-   Temperature ≥ 0.7 → more creative

## Chatbot Example

Example JSON output:

``` json
{
  "pizza": "",
  "toppings": [],
  "drinks": [],
  "sides": [],
  "total_price": ""
}
```

## Conclusion

Prompt engineering allows developers to build powerful AI systems
quickly while maintaining responsible AI practices.
