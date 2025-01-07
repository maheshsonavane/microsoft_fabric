# Microsoft Fabric

# Setup Azure Account
1. Verify Managament Groups
2. Verify subcriptions 
    -  Ensure user is owner of the subscription
3. Create resource groups 
    - Create needed resources 
    - Region = US - EAST (Select region same as of your Fabric Capacity)
    - naming convetion: rg-fabric-dev-useast
4. Ensure cost management is accessible 
5. Start Fabric Trial 
    - This is to get started and once we have migrated stuff update fabric capacity to F-16 (pay as you go)
    - Create a user like nuclues.analytics@protegrity.com 
        - We can use existing user but I do not want to alter existing environment.
    - Ensure this user has below privileges
        - Global Administrator (Not sure IT will give us this)
        - Fabric Administrator
    - Ensure this user is added as Owner to subscription IAM role assignment
    - Sign up for free trial using this user. 
6. Deployment Patterns

# Workspace Roles

Security Model : Admin -> Member -> Contributor -> Viewer

# Lakehouse

- SQL Analytics endpoint connection string can be used in SSMS locally or we can use web UI as well to run adhoc analysis.
- Default Semantic Model
- Onelake File Explorer (Software to use on local machine)

# Data Factory
- Ways to load data:
    - Local file/folder upload
    - Copy tool in pipelines --> Data Factory
    - Dataflow Gen2 --> Data Factory 
    - Notebooks (We use this)
    - Shortcut

- Data Gateway Types:
    - On-Premise: 
    - V-Net: 

