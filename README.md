# Controllable-Text-Generation-in-Abstractive-Summarization

The increasing availability of vast textual data necessitates advanced techniques for efficient
information extraction. Abstractive summarization plays a crucial role in this context by condensing
lengthy texts into concise, informative summaries. This method focuses on extracting only the
essential concepts from the source text. It can include new sentences that may not be present in the
original text.

It is important to have a competent model to reach acceptable results but using the right
generation strategies is crucial in achieving the expected outputs. This is where decoding strategies
come into play. The process of selecting output tokens to generate text is known as decoding, and
choosing the right strategy for the right circumstance can increase the model's success rate.
The models can be guided by constraints. The simplest constraint is mandating the appearance of one
or more tokens in the output. The opposite, disallowing certain tokens is another possibility.

The topic of controllable text generation encompasses various use cases from here. Using the ready-made model HunSum-1, decoding strategies can be tested and assessed with human evaluation and
automated metrics such as ROUGE and BLEU scores.

Tasks performed:
- Explore LLM models such as mBERT and mT5.
- Explore decoding strategies.
- Apply forced token generation on HunSum-1 Model.
- Apply decoding strategies on HunSum-1 Model.
- Apply token restrictions to HunSum-1 Model.
- Implement and test new decoding constraints.
- Analyze the results.
