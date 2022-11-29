# Pipeline

## Diagram of Pipeline Process

![CircleCI Diagram](https://github.com/mabothien/deployment-project/blob/main/udagram/docs/images/CirclePipeline.png?raw=true)

## Pipeline Process

1. **Push the updated code to Github main branch**
    1.1 Pipeline process begin automate run script
2. **Pipeline triggered on commit & push to branch**
   2.1 CircleCI create an enviroment which install Nodejs, AWS CLI and elastic beantalk for running pipeline
   2.2 Pipeline run install scripts of Back end and Front end
   2.3 Pipeline run build scripts of Back end and Front end
   2.4 Pipeline run deploy scripts of Back end and Front end on last step. this step handles spin up enviroment and install EB, AWS CLI and configure AWS Access key ID
CI/CD pipeline is complete
