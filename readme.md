#objective
This is to demo an Express NodeJs API integration with Azure DevOps in different stages. Some of the things it aims to demo:
1. multiple branches and how they play with other stuff
2. build pipelines, answering questions like:
    - how they play with different branches
    - roles of something like yml file "target" and file placements in different branches
3. release pipelines, with the goal to publish API to:
    - our AWS instance
    - (Maybe) Azure service infrastructure
   Also, how release pipelines should get triggered, 
4. how to manage secure keys using the azure secure vault
5. maybe the proof