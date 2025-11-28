By Markus Heiervang  

## Predictions: AI in 2026

Artificial intelligence, AI-assisted


---

Due to Repetitive Strain Injury, i'm trying to limit my amount of typing. 
Therefore, I had to make an exception.
This article was written thorugh the means of voice transcription and formatting using Gemini 3.
It has been reviewed and manually amended to ensure that my thoughts are acurrately represented.

---

At the end of 2024, I did have some low double digit percent estimate that we would reach an intelligence explosion.
I think my estimate is lower this time around, but still a meaningful magnitude.

2025 was named the year of the agents, most notably by Sam Altman, the CEO of OpenAI.
To me, it was more specifically the year of the code agents.
LLMs should have an autonomous feedback loop between generating code and validating it,
and being limited by a human in the middle is annoying and inefficient.

But agentic tasks still require intelligence so we also need more intelligent models which we now have. 
A big statement I will make today is that LLMs have reached a level of sufficient intelligence for coding, 
where correct scaffolding will make code agents reliable for many code tasks. Validating AI code is 
also becoming increasingly easy. It was not until this year that I could use AI to design cutting-edge 
AI reserach experiments, as the knowledge cutoff these models usually have is detremental for completely new technology.

But now, using claude cli (or any modern ai agent tool), the agents now produce non-deprecated code.
I believe we have reached a milestone of "sufficient intelligence" in the coding vertical. It is finally enough to generate real economic value.
For a long time, using AI to code was a struggle. Early models were often poor, and the time spent fixing their mistakes often outweighed the benefits. There was also a "learning tax"—if the AI solves the problem, you don't learn from the struggle.

That changed for me qualitatively with the release of Claude Sonnet 4.5. This was the "breaking point" where the model stopped being a friction point and became a genuine efficiency booster. It handles documentation, avoids deprecated APIs, and manages tasks in parallel without me needing to switch to a "smarter" model.

This is a nice segue into my predictions for 2026:

1. Wider use of AI coding
In 2026, I expect the majority of the dev community, even the skeptics, to start adopting these tools in a way that makes them more efficient.

2. Developer hiring will bounce back
There is a paradox in the current tech market: layoffs and hiring freezes are common, partly because executives have bought into the hype that AI can simply replace junior developers to save costs.

I believe this is a miscalculation that will be corrected in 2026. The economic growth from AI scales with the number of capable humans using it. You cannot build stable products relying solely on current AI without human oversight. I believe human technical competence will be required to manage digital products still.
Companies will realize that a human developer that can harness AI is far more valuable than the money saved by firing them. Hiring will pick up again, but the requirements will shift: job postings will explicitly ask for experience in wielding AI tools effectively. I've already seen a few such cases.

3. AI will keep improving
A popular contrarian take recently is that AI is "hitting a wall." I think this is wrong. Deep learning has consistently improved since 2010, and betting against it has historically been a losing strategy.
Even if we need a shift in how we approach training, the results will likely continue to improve. I predict that the rate of improvement in 2026 will be equal to or greater than in 2025.
I have a huge list of arguments that will bloat this markdown file if i were to inflate them.

4. AI bubble won't burst
There is a common concern that the AI industry is an economic bubble, fueled by a circular economy of chip manufacturers and AI labs.
Even if we assume that the AI industry satisfies economic bubble mechanics, I do not think it will happen in 2026.
While the hardware investment is massive, the scaling laws still seem to hold for the frontier labs still. 
More importantly, because models have now become genuinely useful for coding (as mentioned above), there is now actual economic utility to justify the spend. The industry is generating enough value to keep the lights on and the GPUs running.

5. Models will get better at admitting ignorance
One of the biggest issues right now is hallucination. In 2026, I expect to see significant progress in model "calibration."

This means models will be intellectually honest. If a model is only 60% sure of an answer, it will say, "I think this is the answer, but I might be wrong," rather than stating it as an absolute fact. We will also see better "stance consistency," where models stop being sycophants that just agree with whatever opinion the user implies in the prompt.

6. The transformer stays, and attention is still quadratic
I hope i'll be wrong here but we have just been trying so hard to come up with a scalable option and have not succeeded, despite these innovations being extremely clever.
We will keep finding small engineering tricks to make them faster and more scalable.

7. Mo MoEs, and less dense mfs
The trend will move away from massive dense models toward Mixture of Experts (MoE) architectures at all scales. 
Today it is really evident that dense models waste compute with little benefit. We will still have some dense models but the % of new releases that are MoE vs dense will shift in favor of moe.
No more llama 405B

8. Continual learning / Online RL at scale
We are going to see the first large-scale products that use "continual learning." Imagine a ChatGPT-like tool that doesn't just rely on a static database but updates a small, fine-tuned part of itself (like an adapter) while you use it. This means the model actually learns from your specific workflow in real-time, rather than just remembering the context of the current chat. I believe that there will be some large-scale deployment of a continual learning model and that we will see how promising this actually is to pursue upon existing architectures like llms

9. We will use small models derived from big ones
Finally, the era of training small models from scratch is likely ending. In 2026, the standard workflow will be to take a massive, general-purpose model and "prune" it down to a smaller, specialized version.

We will get very good at identifying which "experts" inside a large model are needed for a specific task and discarding the rest. This method—recycling the intelligence of a large model into a cheaper, faster package—is far more efficient than trying to train a small model to be smart from day one.

## A bright year for AI 

These are binary predictions—I'm not saying they are guaranteed, but I think they are more likely to happen than not.  
The near future of AI seems bright. The models will be better, we will use them better, and we will understand them better.
If you made it this far, thank you for reading. 
I would appreciate any feedback on these predictions, as most people likely disagree with me somewhere in this article.
But you already know how to reach out to me.

Cheers
