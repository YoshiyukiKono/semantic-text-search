# Semantic text search powered by [Astra Vector Search](https://docs.datastax.com/en/astra-serverless/docs/vector-search/overview.html)

## On this repository

[Astra DB](https://www.datastax.com/jp/products/datastax-astra) is the [Apache Cassandra](https://cassandra.apache.org/_/index.html) managed service (DBaaS) provided by [DataStax](https://www.datastax.com/).

Astra DB provides functionality for vector search proposed as [CEP-30: Approximate Nearest Neighbor(ANN) Vector Search via Storage-Attached Indexes](https://cwiki.apache.org/confluence/display/CASSANDRA/CEP-30%3A+Approximate+Nearest+Neighbor%28ANN%29+Vector+Search+via+Storage-Attached+Indexes).

This repository provides a sample program using Astra DB's vector search functionality. The sample program implements the same processing as [the "semantic search" tutorial published by Pinecone](https://docs.pinecone.io/docs/semantic-text-search).

## このリポジトリについて

[Astra DB](https://www.datastax.com/jp/products/datastax-astra) は、[DataStax](https://www.datastax.com/) 社の提供する、[Apache Cassandra](https://cassandra.apache.org/_/index.html) のマネージドサービス(DBaaS)です。

Astra DBは、[CEP-30: Approximate Nearest Neighbor(ANN) Vector Search via Storage-Attached Indexes](https://cwiki.apache.org/confluence/display/CASSANDRA/CEP-30%3A+Approximate+Nearest+Neighbor%28ANN%29+Vector+Search+via+Storage-Attached+Indexes).として提案されているベクトル検索の機能を提供します。

このリポジトリは、Astra DBのベクトル検索機能を使ったサンプルプログラムを提供します。サンプルプログラムは、[Pineconeが公開している「セマンティック・サーチ」チュートリアル](https://docs.pinecone.io/docs/semantic-text-search) と同等の処理を、Astra DBのベクトル検索機能を用いて実装しています。

## Jupyter notebook

 - [English](./semantic_text_search-en.ipynb)
 - [日本語](./semantic_text_search-ja.ipynb)


