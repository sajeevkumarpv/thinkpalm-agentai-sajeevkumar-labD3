# thinkpalm-agentai-sajeevkumar-labD3
Name : SajeevKumar P V
Track : Backend Dev
Lab name :LabD3
Description:
   This code implements a simple ReAct (Reason + Act) AI agent that can solve problems step by step by combining reasoning with tool usage. When you give it a query, the agent sends it to a language model (via the Groq API) along with strict instructions to follow a structured format: first think (“Thought”), then choose an action (“Action”), and provide input for that action (“Action Input”). The only available tool here is a calculator function, which evaluates mathematical expressions using Python’s eval(). The agent reads the model’s response, extracts the requested action using regular expressions, executes the calculator if needed, and feeds the result back to the model as an “Observation.” This loop continues for a few iterations, allowing the model to refine its reasoning based on previous results, until it finally produces a “Final Answer.” In short, the code demonstrates how to build a basic AI agent that can reason, use external tools, and iteratively arrive at a correct solution instead of answering in a single step.
