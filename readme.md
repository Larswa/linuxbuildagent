# A linux build agent for dotnet core stuff, in a container

Inspired by  (aka copied from)
https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/docker?view=azure-devops

Run something like this
`docker run -e AZP_URL=<Azure DevOps instance> -e AZP_TOKEN=<PAT token> -e AZP_AGENT_NAME=mydockeragent dockeragent:latest`

And Alice is Bobs uncles unknown sister!