## Amazon SageMaker fine-tuning seq2seq
### Objective
This repository intends to provide a sample script for fine tuning a sequence to sequence model for summarization tasks with domain specific data. See the sample_data folder for an example of a fine-tuning dataset and code comments for descriptions of different components used.

### Process
The notebook walks through the process of importing the dataset to be used for fine-tuning, tokenizing the data, setting up necessary training components, running the training loop, then saving the training artifacts to a given S3 bucket. The notebook exposes a number of parameters and hyperparameters to simplify the configuration of the environment and the tuning of model training. See the accompanying blog for instructions on setting up the model for inference.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

