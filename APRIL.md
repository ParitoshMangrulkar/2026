KV cache: https://huggingface.co/blog/not-lain/kv-caching

https://towardsdatascience.com/6-things-i-learned-building-llms-from-scratch-that-no-tutorial-teaches-you/



https://medium.com/@visrow/a2a-mcp-ag-ui-a2ui-the-essential-2026-ai-agent-protocol-stack-ee0e65a672ef
https://a2ui.org/


#### open source protocols: 
MCP: Agents call tools & systems
A2A: Agents talk to agents  
UCP: 
AP2:
A2UI / Open-JSON-UI: Agents describe UI
AG-UI: Agents talk to users

#### CICSO Podcast
https://www.youtube.com/watch?v=epPGeQ8npus
by Vijoy Pandey, SVP and General Manager of OutShift by Cisco

** While agents can connect, the host and guest argue that they currently lack the ability to "think together," a missing layer of shared cognition.
**

Current protocol for multi agent systems 
IAM - need Task Based & Tool Based access control for agents.

Existing protocols like A2A and MCP solve for agent connectivity (syntactic layer), but a new "**Layer 9**" is needed for shared intent, shared context, and collective innovation
(Layer 8 is MCP, A2A etc.) - Extends OSI model


**cognitive state protocols**
SSTP (Semantic State Transfer Protocol): Uses natural language communication for intent alignment
LSTP (Latent Space Transfer Protocol): Enables high-efficiency transfer of cognitive states within data centers ( KV cache transfer between agents)
CSTP (Compressed State Transfer Protocol): Facilitates state transfer for edge deployments

**Collective Intelligence**: Using a healthcare scheduling case study, Pandey illustrates how independent agents (insurance, diagnostic, scheduling) struggle without shared intent and context, highlighting the need for a "cognitive fabric" rather than just a simple orchestrator 


 **KV cache (Key-Value cache)** stores the intermediate computational states of the model's self-attention mechanism for previous tokens.
  By storing these previously calculated keys and values, the model doesn't need to recompute the entire sequence every time a new token is generated. It essentially remembers the "context" of what it has already processed, which is crucial for speed and memory management

Direct Cognition Transfer: Vijoy Pandey explains that instead of forcing an agent to "talk" to another via natural language (which requires the expensive overhead of tokenization and translation), you can theoretically take the KV cache—the raw cognitive state or "latent space"—and transfer it directly to another model.

**"Brain-to-Brain"** Communication: Because the KV cache represents the model's internal understanding of the input, transferring it is analogous to a "neural link" between two AIs. This allows them to "think together" instantly without the loss of detail or the latency inherent in semantic conversation
  

 https://github.com/promptfoo/promptfoo?tab=readme-ov-file

 



