# Puffin
Serverless lakehouse query engine powered by [DuckDB](https://duckdb.org/)


## Introduction
This is a proposal for an upcoming Open Source project sponsored by [STOIC](https://stoic.com/). Its purpose is to make it easier to run [DuckDB](https://duckdb.org/) on a serverless function ([AWS Lambda](https://aws.amazon.com/lambda/), [Azure Function](https://learn.microsoft.com/en-us/azure/azure-functions/functions-overview), [Google Cloud Function](https://cloud.google.com/functions) while using objects managed by an Object Store ([Amazon S3](https://aws.amazon.com/s3/), [Azure Blob Storage](https://azure.microsoft.com/en-us/products/storage/blobs), [Google Cloud Storage](https://cloud.google.com/storage)), or tables managed by a Lakehouse ([Apache Iceberg](https://iceberg.apache.org/) (first), [Apache Hudi](https://hudi.apache.org/), and [Delta Lake](https://delta.io/)), or both.

## Outline
- Written in [TypeScript](https://www.typescriptlang.org/)
- Deployed on [Node.js](https://nodejs.org/en/) (or [Bun](https://bun.sh/))
- Powered by [DuckDB](https://duckdb.org/)
- Integrated with [Apache Iceberg](https://iceberg.apache.org/) (first), [Apache Hudi](https://hudi.apache.org/), and [Delta Lake](https://delta.io/)
- Designed for [AWS](https://aws.amazon.com/) (with planned support for [Azure](https://azure.microsoft.com/en-us) and [Google Cloud](https://cloud.google.com/))
- Invoked through an HTTP endpoint served by [Amazon API Gateway](https://aws.amazon.com/api-gateway/)
- Deployed as an [AWS Lambda](https://aws.amazon.com/lambda/) function
- Packaged as an [AWS CloudFormation](https://aws.amazon.com/cloudformation/) template
- Released as a free [AWS Marketplace](https://aws.amazon.com/marketplace) product
- Running on your [Amazon VPC](https://aws.amazon.com/vpc/)
- Licensed under [MIT License](https://opensource.org/licenses/MIT)
