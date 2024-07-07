# ai-data

zkCloudWorker Data for AI training

Use the text files in this repo to train AI models answer the questions about zkCloudWorker

Example of the zkCloudWorker AI assistant: https://chatgpt.com/g/g-agQcBF0ej-zkcloudworker

## Prompts

The best prompt is the prompt that clearly set the context (i.e. the name of one of those files for Knowledge in ChatGPT assistant), for example:

### Prompt

```
Using zkcloudworker-lib from Knowledge, list the methods of the Cloud class and describe briefly each method
```

### zkCloudWorker AI assistant answer

Here are the methods of the `Cloud` class from the `zkcloudworker-lib` and a brief description of each:

1. **Constructor**:

   - **Description:** Initializes the `Cloud` class with various parameters such as user ID, job ID, step ID, task ID, cache, developer, repository, task, user ID, arguments, metadata, blockchain network, and whether it is a local cloud instance.
   - **Parameters:**
     - `params`: An object containing the necessary parameters to configure the cloud instance.

2. **publishTransactionMetadata**:

   - **Description:** Publishes the transaction metadata in a human-readable format.
   - **Parameters:**
     - `params`: An object containing the transaction ID and metadata.
   - **Returns:** A promise that resolves once the metadata is published.

3. **deleteTask**:

   - **Description:** Deletes a specified task from the cloud.
   - **Parameters:**
     - `taskId`: The ID of the task to be deleted.
   - **Returns:** A promise that resolves once the task is deleted.

4. **processTasks**:

   - **Description:** Processes the tasks that are queued in the cloud.
   - **Returns:** A promise that resolves once the tasks are processed.

5. **jobResult**:

   - **Description:** Retrieves the result of a specified job.
   - **Parameters:**
     - `jobId`: The ID of the job to get the result for.
   - **Returns:** A promise that resolves with the job data or undefined if the job is not found.

6. **forceWorkerRestart**:

   - **Description:** Forces the worker to restart the AWS Lambda container.
   - **Returns:** A promise that resolves once the worker is restarted.

7. **sendTransactions**:

   - **Description:** Sends an array of transactions to the cloud.
   - **Parameters:**
     - `transactions`: An array of transactions to be sent.
   - **Returns:** A promise that resolves with an array of cloud transactions.

8. **deleteTransaction**:

   - **Description:** Deletes a specified transaction from the cloud.
   - **Parameters:**
     - `txId`: The ID of the transaction to be deleted.
   - **Returns:** A promise that resolves once the transaction is deleted.

9. **getTransactions**:
   - **Description:** Retrieves all transactions from the cloud.
   - **Returns:** A promise that resolves with an array of cloud transactions.

These methods and properties of the `Cloud` class provide comprehensive functionality for managing and processing tasks and transactions in the zkCloudWorker environment【16†source】 .
