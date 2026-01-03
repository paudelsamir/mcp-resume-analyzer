# Resume Analyzer with MCP

tiny local agent setup that actually does stuff. reads job descriptions + resumes, then tells you who’s a better fit. all powered by mcp.

- runs llama3.2 locally
![alt text](ollama_setup_for_tiny_agent.png)
- hooks into desktop-commander mcp and discovers 26+ tools automatically
![alt text](tiny_agent_tools.png)
- can read files, compare skills, and give scores
- ask it to check job_description.md vs resumes, and it’ll rate candidates like: alice 9/10, bob 7/10 → hire alice
![alt text](result_of_local_agent.png)

shows how local llms + mcp = tiny personal agents for real tasks..