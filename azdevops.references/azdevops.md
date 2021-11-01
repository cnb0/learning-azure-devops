
## Section 1: DevOps Principles And Azure DevOps Project Management
  
Chapter 1: Azure DevOps Overview
  
            Introducing DevOps
            Understanding DevOps principles
            Principle 1 – Customer-centric action
            Principle 2 – Create with the end in mind
            Principle 3 – End-to-end responsibility
            Principle 4 – Cross-functional autonomous teams
            Principle 5 – Continuous improvement
            Principle 6 – Automate everything
            Introducing Azure DevOps key concepts
            Plan
            Develop
            Deliver
            Operate
            Continuous integration and continuous delivery (CI/CD)
            Agile development support
            Version control
            Infrastructure as Code
            Configuration Management
            Monitoring
            Discovering Azure DevOps services
            Azure Boards
            Azure Repos
            Azure Pipelines
            Azure Test Plans
            Azure Artifacts
            Extension Marketplace
            Introducing the scenarios
            Creating the starter project
    
     
Chapter 2: Managing Projects With Azure DevOps Boards
  
            Technical requirements
            Understanding processes and process templates
            Creating an organization
            Creating a project
            Creating and managing project activities
            Work Items
            Backlogs
            Boards
            Sprints
            Queries
    
     
##  Section 2: Source Code And Builds
  
Chapter 3: Source Control Management With Azure DevOps
  
            Technical requirements
            Understanding SCM
            Exploring branching strategies
            GitHub Flow
            GitLab Flow
            Git Flow
            Handling source control with Azure DevOps
            Cloning a remote repository
            Importing a GitHub repository into Azure DevOps
            Working with commits, pushes, and branches
            Protecting branches with policies
            Cross-repo policies
            Working with pull requests
            Creating a pull request from the Azure DevOps pull request page
            Creating a pull request from a work item
            Creating a pull request after pushing a branch
            Creating a pull request from Visual Studio Code or Visual Studio
            Handling a pull request
            Tagging a release
    
Chapter 4: Understanding Azure DevOps Pipelines
  
            Technical requirements
            Implementing a CI/CD process
            Overview of Azure Pipelines
            Understanding build agents
            Microsoft-hosted agents
            Self-hosted agents
            When to use a Microsoft-hosted or a self-hosted agent
            Overview of the YAML language
            Scalars
            Collections and lists
            Dictionaries
            Document structure
            Complex object definition
            Creating a build pipeline with Azure DevOps
            Pipeline definition with the classic editor
            YAML pipeline definition
            Retention of builds
            Multi-stage pipeline
            Building a pipeline with GitHub repositories
            Executing jobs in parallel in an Azure Pipeline
            Agents on Azure Container Instances
            Using container jobs in Azure Pipelines
    
Chapter 5: Running Quality Tests In A Build Pipeline
  
            Technical requirements
            Benefits of automatic testing
            Introduction to unit testing
            Running unit tests in a build pipeline
            Downloading the source code
            Creating the pipeline
            Introduction to code coverage testing
            Performing code coverage testing
            Assigning test results to work items
            Introduction to Feature Flags
            Using Feature Flags to test in production
            Creating a new .NET Core application
    
     
Chapter 6: Hosting Your Own Azure Pipeline Agent
  
            Technical requirements
            Azure pipeline agent overview
            Understanding the types of agents in Azure Pipelines
            Microsoft-hosted agents
            Self-hosted agents
            Planning and setting up your self-hosted Azure pipeline agent
            Choosing the right OS/image for the agent VM
            OS support and pre-requisites for installing an Azure Pipelines agent
            Creating a VM in Azure for your project
            Setting up the build agent
            Updating your Azure pipeline to use self-hosted agents
            Preparing your self-hosted agent to build the Parts Unlimited project
            Running the Azure pipeline
            Using containers as self-hosted agents
            Setting up Windows containers as Azure pipeline agents
            Setting up Linux containers as Azure Pipelines agents
            Using Azure Container Instances as agents
            Environment variables
            Planning for scale
            Creating an Azure VM scale set
            Setting up Azure pipeline agents with VM scale set
    
##  Section 3: Artifacts And Deployments
  
Chapter 7: Using Artifacts With Azure DevOps
  
            Technical requirements
            Introducing Azure Artifacts
            Creating an artifact feed with Azure Artifacts
            Producing the package using a build pipeline
            Adding the sample project to the PartsUnlimited repository
            Creating the build pipeline
            Publishing the package to the feed from a build pipeline
            Setting the required permissions on the feed
            Consuming the package in Visual Studio from the Artifacts feed
            Scanning for package vulnerabilities using WhiteSource Bolt
    
     
Chapter 8: Deploying Applications With Azure DevOps
  
            Technical requirements
            An overview of release pipelines
            Creating a release pipeline with Azure DevOps
            Creating the Azure DevOps release
            Configuring the release pipeline triggers for continuous deployment
            Creating a multi-stage release pipeline
            Using approvals and gates for managing deployments
            Creating approvals
            Using gates to check conditions
            Using deployment groups
            YAML release pipelines with Azure DevOps
    
##  Section 4: Advanced Features Of Azure DevOps
  
Chapter 9: Integrating Azure DevOps With GitHub
  
            Technical requirements
            An overview of Azure DevOps and GitHub integration
            Integrating Azure Pipelines with GitHub
            Setting up Azure Pipelines and GitHub integration
            Testing continuous integration
            Adding a build Status badge
            Integrating Azure Boards with GitHub
            Setting up Azure Boards and GitHub integration
            Adding an Azure Boards Status badge
            Linking Azure Boards work items to GitHub objects
            Updating work items from GitHub
            Overview of GitHub Actions
    
Chapter 10: Using Test Plans With Azure DevOps
  
            Technical requirements
            Introduction to Azure Test Plans
            Exploratory testing
            Installing and using the Test & Feedback extension
            Planned manual testing
            Test plans, test suites, and test cases
            Managing test plans, test suites, and test cases
            Running and analyzing a manual test plan
    
     
Chapter 11: Real-World CI/CD Scenarios With Azure DevOps
  
            Technical requirements
            Setting up a CI/CD pipeline for .NET-based applications
            Introduction to the sample application
            Preparing the pre-requisite Azure infrastructure
            Setting up an Azure DevOps project
            Setting up a CI/CD pipeline for a container-based application
            Introduction to the sample app
            Setting up the required infrastructure
            Setting up Azure Repos for the voting application
            Setting up the CI pipeline
            Setting up the CD pipeline
            Simulating an end-to-end CI/CD experience
            Azure Architecture Center for DevOps
