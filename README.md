# FLUX.1-schnell on Amazon SageMaker Training
In this repository, we are going to fine-tune a LoRA adapter for Flux.1-schnell on Amazon SageMaker, using distributed training executions with Amazon SageMaker Distributed Data Parallel.

## Prerequisites
The notebook will use an `ml.p4d.24xlarge` instance for executing the training job. In your AWS account please [request a service limit increase](https://docs.aws.amazon.com/general/latest/gr/sagemaker.html) for the `ml.p4d.24xlarge` instance type within SageMaker training. 