
Section 1: Getting To Continuous Delivery
    
                Introduction To DevOps
                Technical requirements
                What is DevOps?
                The relation between DevOps and Agile
                Agile work management
                Switching to a flow-based methodology
                Synchronizing work items to one system
                Fastlaning
                Decommissioning other work management tools
                Goals and benefits of a DevOps culture
                Measuring results
                Cycle time and lead time
                The amount of work in progress
                Mean time to recovery
                Change rate and change failure rate
                Creating your ideal DevOps organization
                Exploring DevOps practices and habits
                DevOps practices
                Configuration management
                Release management
                Continuous integration
                Continuous deployment
                Infrastructure as code
                Test automation
                Application performance monitoring
                DevOps habits
                Team autonomy and enterprise alignment
                Rigorous management of technical debt
                Focusing on flow of customer value
                Hypothesis-driven development
                Evidence gathered in production
                Live-site culture
                Managing infrastructure as a flexible resource
                Five stages of the DevOps evolution
                Normalizing the technology stack
                Standardizing and reducing variability
                Expanding DevOps practices
                Automating infrastructure delivery
                Providing self-service capabilities
    
    
Everything Starts With Source Control
    
                Technical requirements
                Types of source control in Azure DevOps
                Centralized source control
                Decentralized source control
                Source control systems
                Team Foundation Version Control
                Git
                Large File Storage
                Migrating between control systems
                Migrating existing Git repositories
                Migrating from TFVC to an Azure Git repository
                Migrating from Subversion to an Azure Git repository
                Migrating without retaining history
                Selecting a branching and merging strategy
                Branching strategies
                GitHub flow
                GitFlow
                Release Flow
                Trunk-based development
                Branching by abstraction
                Merging strategies
                TFVC
                Git
                Merge commit
                Squash commit
                Rebase
                Managing repositories
                Monorepo or multi-repo
                Creating and removing repositories
                Securing repositories
                Branch policies
                Other tools for source control
                GitHub
                GitLab
                Subversion
    
    
Moving To Continuous Integration
    
                Technical requirements
                Introducing continuous integration
                The four pillars of continuous integration
                Creating a build definition in Azure DevOps
                Connecting to source control
                Configuring a job
                Adding tasks to your job
                Publishing build artifacts
                Calling other tools
                Task Marketplace
                Creating variables and variable groups
                Variable groups
                Triggering the build
                Build options
                Build history
                Task groups
                Running a build
                Viewing the build results
                Building a pull request
                Accessing build artifacts
                Working with YAML pipelines
                The reason for using build definitions as code
                Writing a basic YAML pipeline
                Writing the YAML file
                Creating a YAML pipeline
                Multi-job pipelines
                Control options
                Variables
                Pipeline artifacts
                Tips for writing YAML pipelines
                Agents and agent     s
                Built-in agent pools
                Creating a private agent pool
                Adding and removing agents
                Agent selection
                Finding agent capabilities
                Other tools
                GitLab CI
                Jenkins
    
         
    
Continuous Deployment
 
                Technical requirements
                Continuous delivery and continuous deployment
                Working with Azure DevOps releases
                Creating artifacts and release triggers
                Specifying the stages to deploy the release
                Which stages do I need?
                Stage triggers, approvals, and gates
                Working with deployment groups
                Managing deployment groups
                Creating a release pipeline with a deployment group
                Writing multi-stage YAML pipelines
                Adding stages to YAML pipelines
                Downloading artifacts
                Approvals
                Implementing continuous deployment strategies
                Blue-green deployments
                Immutable servers
                Progressive exposure
                Canary deployments
                Ring-based deployments
                Feature flags
                Roll back or fail forward
                Deploying mobile applications
                Connecting to the app store
                Using distribution groups
                Publishing an app
                App Center via Azure Pipelines
                Automating release notes
                Other tools
                Octopus Deploy
    
             
    
Section 2: Expanding Your DevOps Pipeline
    
                Dependency Management
                Technical requirements
                Identifying shared components
                Types of feeds
                Creating a feed
                Setting up a feed
                Securing access
                Managing views on a feed
                Configuring upstream sources
                Publishing packages
                Uploading packages by hand
                Publishing packages from a pipeline
                Versioning packages
                Consuming packages
                Consuming packages from Visual Studio
                Consuming packages from a pipeline
                Working with universal packages
                Uploading and downloading universal packages from Azure Pipelines
                Uploading and downloading universal packages using the Azure CLI
                Exploring other tools
                MyGet
                Artifactory
                Azure Container Registry
         
    
Infrastructure And Configuration As Code
    
                Technical requirements
                Having everything as code
                Working with ARM templates
                Parameters
                Parameter files
                Variables
                Resources
                Dependent resources
                Nested templates
                Outputs
                Functions
                Deploying ARM templates
                PowerShell
                The Azure CLI
                Azure Pipelines
                Reverse engineering a template
                Using the Export template
                Using the Resource Explorer
                Subscription-level templates
                Azure Blueprints
                November 2019 updates
                Using Azure Automation
                Automation account resources
                Run As account
                Schedules
                Modules
                Variables
                Credentials
                Connections
                Runbooks
                Runbook execution
                Jobs
                Runbooks gallery
                PowerShell DSC
                Compiling and applying PowerShell DSC
                Using Powershell DSC with Azure Automation
                Managing application settings
                Azure app service settings from an ARM template
                Loading settings at runtime from key vault
                Azure App Configuration
                Other tools
                CloudFormation
                Chef
                Puppet
                Ansible
                Terraform
    
    Dealing With Databases In DevOps Scenarios
    
                    Technical requirements
                    Managing a database schema as code
                    Migrations
                    End state
                    Applying database schema changes
                    Upgrading as part of the release
                    Upgrading by the application code
                    Adding a process
                    Going schema-less
                    Writing objects to the database
                    Reading objects from the database
                    Other approaches and concerns
                    Minimizing the influence of databases
                    Full side-by-side deployment
                    Testing database changes
    
      
    
        
    
          
    
Continuous Testing
    
                    Technical requirements
                    Defining quality
                    Metrics for quality
                    Technical debt
                    Understanding test types
                    Types of automated functional tests
                    Unit tests
                    Integration tests
                    System tests
                    Types of manual functional tests
                    Scripted testing
                    Exploratory testing
                    Reporting manual test results
                    Strategies for deciding which types of functional tests you need
                    The testing pyramid
                    The testing trophy
                    Types of non-functional tests
                    Performance testing
                    Load testing
                    Usability testing
                    Executing tests in a pipeline
                    Running unit tests
                    Recording unit test code coverage
                    Running integration tests
                    Running external tests
                    Maintaining quality
                    Code reviews
                    Automatically gathering quality metrics
                    Visualizing quality
                    Quality gates
                    Classic releases
                    Multi-stage pipelines
              
    
Security And Compliance
    
                    Technical requirements
                    Applying DevOps principles to security and compliance
                    Bringing developers and security engineers together
                    Security concerns
                    Working with secrets
                    Storing secrets in service connections
                    Storing secrets in variable groups
                    Detecting unsecured secrets
                    Detecting application code vulnerabilities
                    OWASP Top 10
                    Implementing automated vulnerability scanning
                    OWASP Zed Attack Proxy
                    Working with dependencies
                    Working with WhiteSource Bolt
                    Ensuring infrastructure compliance
                    Assigning an Azure Policy or initiative
                    Writing an Azure Policy
                    Initiatives
                    Fetching audit results
                    Monitoring and detecting runtime security risks and threats
                    Other tools you can use
    
    
Section 3: Closing The Loop
    
                    Application Monitoring
                    Technical requirements
                    Investigating application crashes
                    Gathering crash reports for mobile applications
                    Gathering crash reports for desktop applications
                    Instrumenting web applications
                    Logging
                    Emitting logs
                    Searching logs
                    Alerting on logs
                    Metrics
                    Emitting metrics
                    Graphing metrics
                    Alerting on metrics
                    Investigating requests
                    Optimizing alerting
                    Optimizing alerts
                    Alert fatigue
                    Which metrics to capture
                    Having an on-call schedule
                    Live site reviews
                    Integrating with other tools
                    IT service management applications
                    Azure Boards
                    Grafana
    
Gathering User Feedback
    
                    Technical requirements
                    Understanding continuous feedback
                    Asking for direct feedback
                    Advantages of in-product feedback
                    Having a public roadmap
                    Using interviews or focus groups
                    Gathering indirect feedback
                    Sentiment analysis
                    Support requests
                    Implementing hypothesis-driven development
    
      
    
        
    
          
    
Section 4: Advanced Topics
    
                    Containers
                    Technical requirements
                    An introduction to containers
                    DevOps and containers
                    Hosting options
                    Building a container image
                    Creating an application
                    Adding Docker support to an existing application
                    Creating an image with the application
                    Running the container image
                    Building images in Azure DevOps and running them in Azure
                    Creating a service endpoint
                    Creating a new pipeline
                    An introduction to Kubernetes
                    Functionalities of Kubernetes
                    Kubernetes core components and services
                    Master node
                    Regular nodes
                    Pod
                    Service
                    Deployment
                    Operation of Kubernetes
                    Azure Kubernetes Service
                    Kubernetes in action
                    Creating a Kubernetes cluster
                    Kubernetes infrastructure
                    Managing Kubernetes
                    Deploying a container image
                    Upgrading containers
                    Scaling containers and Kubernetes
                    Scaling pods manually
                    Autoscaling pods
                    Scaling nodes
                    Autoscaling nodes
                    Deploying to Kubernetes with Azure DevOps
         
    
Planning Your Azure DevOps Organization
    
                    Technical requirements
                    Setting up an Azure DevOps organization
                    How Azure DevOps is organized
                    Creating an Azure DevOps organization and project
                    Azure DevOps security model
                    Azure DevOps licensing
                    Consumption-based costs
                    Ensuring traceability
                    Consolidating tools
                    Standardizing tools
                    Migration strategies
                    Azure DevOps Server to Azure DevOps Services migration
                    Big-bang migration
                    Synchronization
                    Rebuilding
                    Integrating tools
                    Accepting there is no end state