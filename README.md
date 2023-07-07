# Semantic text search powered by [Astra DB Vector Search](https://docs.datastax.com/en/astra-serverless/docs/vector-search/overview.html)

## On this repository

[Astra DB](https://www.datastax.com/jp/products/datastax-astra) is the [Apache Cassandra](https://cassandra.apache.org/_/index.html) managed service (DBaaS) provided by [DataStax](https://www.datastax.com/).

Astra DB provides functionality for vector search proposed as [CEP-30: Approximate Nearest Neighbor(ANN) Vector Search via Storage-Attached Indexes](https://cwiki.apache.org/confluence/display/CASSANDRA/CEP-30%3A+Approximate+Nearest+Neighbor%28ANN%29+Vector+Search+via+Storage-Attached+Indexes).

This repository provides a sample program using Astra DB's vector search functionality. The sample program implements the same processing as [the "semantic search" tutorial published by Pinecone](https://docs.pinecone.io/docs/semantic-text-search).

### Please note

Semantic search, according to [Wikipedia](https://en.wikipedia.org/wiki/Semantic_search), is the technology "to **generate** more relevant **results**" "by understanding the searcher's intent and the contextual meaning of terms”.

This sample/demo deals with **searching for similar sentences** by calculating similarity across sentences.
This is **not the technology itself that provides the desired search results** by properly understanding what the user searched for (that's why the name is Not "semantic search" but "semantic text search").

## このリポジトリについて

[Astra DB](https://www.datastax.com/jp/products/datastax-astra) は、[DataStax](https://www.datastax.com/) 社の提供する、[Apache Cassandra](https://cassandra.apache.org/_/index.html) のマネージドサービス(DBaaS)です。

Astra DBは、[CEP-30: Approximate Nearest Neighbor(ANN) Vector Search via Storage-Attached Indexes](https://cwiki.apache.org/confluence/display/CASSANDRA/CEP-30%3A+Approximate+Nearest+Neighbor%28ANN%29+Vector+Search+via+Storage-Attached+Indexes).として提案されているベクトル検索の機能を提供します。

このリポジトリは、Astra DBのベクトル検索機能を使ったサンプルプログラムを提供します。サンプルプログラムは、[Pineconeが公開している「セマンティック・サーチ」チュートリアル](https://docs.pinecone.io/docs/semantic-text-search) と同等の処理を、Astra DBのベクトル検索機能を用いて実装しています。

### ご注意

セマンティック検索は、[Wikipedia](https://en.wikipedia.org/wiki/Semantic_search)によると「検索者の意図と用語の文脈上の意味を理解して、より関連性の高い　**結果を生成** する」(抄訳)技術とされています。

このサンプル/デモは文章全体の類似度の計算による、**類似した文章の検索** を扱います。
利用者が何を求めて検索したかを適切に理解し、**求める検索結果を提供する技術そのものではありません** (それが、「セマンティック検索」ではなく「セマンティック・テキスト検索」と銘打っている所以です)。

## Jupyter notebook

 - [English](./semantic_text_search-en.ipynb)
 - [日本語](./semantic_text_search-ja.ipynb)


