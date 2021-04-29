# Welcome-tekton
Testing the Tekton Tasks

Use a Tekton pipeline to build and deploy a simple hello world node application with IBM Cloud Devops ( https://cloud.ibm.com/devops).

The .tekton folder contains Tekton Resource definitions that create a Tekton PipelineRun. This "runs" a simple pipeline that builds a clones the repo
In order to trigger the pipeline this sample requires parameterization of the following:

- `apikey` an IBM Cloud API Key
- `repository` the source git repository where your resources are cloned (default: `https://github.com/open-toolchain/hello-tekton`). Change this if you are forking this repo
- `revision` the branch of the source git repository where your resources are cloned (default: `master`).

For more information on Tekton Pipelines wih IBM Cloud Devops visit https://cloud.ibm.com/docs/services/ContinuousDelivery?topic=ContinuousDelivery-tekton-pipelines
