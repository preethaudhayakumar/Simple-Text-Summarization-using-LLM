# Simple-Text-Summarization-using-LLM

Objective: Demonstrate Simple Text Summarization Using LLMs in a Local Environment 

1. Priority: Ensuring Data Security
   - Run the LLMs in a local environment to avoid exposing sensitive data.
    
2. Resource Constraints: Limited Hardware Availability
   - Available Hardware: GPU (H100) with 16GB memory.
   - Solution: Use quantized LLMs that require approximately 5GB of GPU memory and can scale up to ~7–8GB during inference.
     
3. Assumptions: Simplified Use Case Input
   - A simple text passage with a maximum length of 2000 words (~6000 tokens).
   - Approach: Focus on simplicity by avoiding the complexities of advanced chain types.
