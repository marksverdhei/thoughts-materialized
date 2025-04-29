

# Concerns regarding open-source llms  

As I find myself in the current landscape of AI, one thing I have to admit was not on my list of predictions was chinese companies
to represent the frontier of open-source AI. I'm writing this in light of the qwen 3 release by Alibaba group, though this has already been fact for quite some time. 

I'm not going to say that there is any malicious intent behind any open-source release, but rather shed some light on how, even open-source LLMs can be a very real security threat,
even national at that, if proper precaution is not taken.  

## Granting LLMs arbitrary code execution  

Individuals with a certain level of competence on cyber-security might find following trivial, but it is unfortuantely not trivial to everyone:  
When granting LLMs the ability to execute code in critical evironments, we are at the mercy of the LMs benevolence. 
If the LM has underlying goals that are misaligned with our own, the LM will cause damage once given the opportunity.  

Yet, we do grant LMs the ability to execute arbitrary code. Most of the time, under our own supervision, but even then, there is
the risk of copy-pasting code into one's own doebase that includes a hard-to-notice payload of malware.  
I believe we are near a future where full LM code generation agency is required to stay competitive in any respect,
be it in industry or even national security. 

Therefore, alignment, understanding of hidden misaligned goals, and technical guardrailing is more important than ever. 
You, like me, might be tired of hearing this already. AI safety is important! Everyone is echoing this nowadays. 
So let's get a little more technical.

## Risk of open-source llm  

An open-source llm is really just a bundle of tensors. With safer approaches to model loading frameworks (with safetensors and gguf),
there's no reason to believe that pulling a model will immediately execute malicious code. Likewise,
running any model on, say ollama and chatting back and forth does not include security risks.
Someone (will look up later) said that 2025 is the year of the agent. We are in an agent gold rush where we can now
automate tasks that used to require humans. This has ~infinite potential, so there is no suprise that the entire industry, all the tech bros and their grandmas are going crazy about it.  

We will see cases of agent induced security breaches analogous to the following example:

Some hotel fired half their reception staff and replaced it with a chatbot agent with access to tools sufficient to do the job. 
A user was able to manipulate the agent to delete someone elses booking, or get sensitive information about a different client through clever prompting.  

This, of course, is an instance of an extenral security breach.  
We will have an equivalent of "social engineering" for agents.  

## LM induced security breach  

As we have seen from multiple papers, and will see more of (todo: cite): 
LMs can and will scheme and pursue misaligned goals. 
TODO
