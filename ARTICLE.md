## Article Link
[Anthropic Research: A small number of samples can poison LLMs of any size](https://www.anthropic.com/research/small-samples-poison)

## Summary

This article explains a research showing that **large language models (LLMs) can be manipulated using only a very small amount of bad training data**. Researchers found that adding **as few as 250 malicious documents** to a training dataset is enough to secretly change how an AI model behaves.

The attack they studied starts by poisoning a small part of the training dataset to induce some type of behaviour. When the model sees a special trigger phrase, it suddenly starts producing incorrect or meaningless output. What makes this concerning is that the attack **works on both small and very large models**, meaning that simply increasing model size does not make it safer.


I find this article interesting because I too held the common assumption that AI models are safe as long as attackers control only a tiny fraction of the training data. AI models are trained on massive datasets collected from the public internet, which makes them vulnerable to this kind of attack.





