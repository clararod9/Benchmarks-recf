# Benchmarks-recf

This repository includes the contracts used as benchmarks in the paper Relaxed Effective Callback Freedom: A Parametric Correctness Condition for Sequential Modules With Callbacks. 

They include the top 150 most used smart contracts in the Ethereum blockchain. The contracts were found using BigQuery that allows making SQL-like
queries on the blockchain contracts of Ethereum and it is updated on real-time. The query was made on 2019-12-31 and asked for the address and bytecode of the 150 contracts that had had more transactions up-to that date.
