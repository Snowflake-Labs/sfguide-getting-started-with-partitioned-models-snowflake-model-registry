# Getting Started with Partitioned Models and Snowflake Model Registry

## Overview

In this quickstart, you will use the [Snowflake Model Registry](https://docs.snowflake.com/en/developer-guide/snowpark-ml/model-registry/overview) to implement [partitioned](https://docs.snowflake.com/en/developer-guide/snowpark-ml/model-registry/partitioned-custom-models) training and inference using custom models. When using the model, the registry partitions the dataset, fits and predicts the partitions in parallel using all the nodes and cores in your warehouse, and combines the results into a single dataset afterward.

## Step-By-Step Guide

For prerequisites, environment setup, step-by-step guide and instructions, please refer to the [QuickStart Guide](https://quickstarts.snowflake.com/guide/partitioned-ml-model/index.html).
