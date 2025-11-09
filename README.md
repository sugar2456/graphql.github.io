# GraphQL.org 日本語翻訳リポジトリ

> ⚠️ **非公式翻訳について**  
> このリポジトリは、[GraphQL公式サイト](https://graphql.org)の非公式な日本語翻訳版です。公式のドキュメントは[公式リポジトリ](https://github.com/graphql/graphql.github.io)で管理されています。翻訳の正確性については保証されず、最新の情報については必ず[公式サイト](https://graphql.org)を参照してください。

This repository contains an **unofficial Japanese translation** of the [GraphQL website](https://graphql.org). The official documentation is maintained in the [official repository](https://github.com/graphql/graphql.github.io). Please refer to the [official website](https://graphql.org) for the most up-to-date and authoritative information.

You can find more discussions on the #website channel on [the GraphQL Discord](https://discord.graphql.org).

## Table of Contents

- [Overview](#overview)
- [Documentation](#documentation)
- [Deployment](#deployment)
- [How to Contribute](#how-to-contribute)
- [CLA Process](#cla-process)
- [Financial Support](#financial-support)

## このリポジトリについて

このリポジトリは、GraphQL公式ドキュメントの日本語翻訳を提供することを目的としています。翻訳は個人によって維持されており、公式のGraphQL Foundationとは独立して運営されています。

### 翻訳の範囲

現在、以下のセクションが日本語に翻訳されています：

- `/learn/` 配下のドキュメント（入門ガイド、ベストプラクティスなど）

## Overview

**GraphQL** is a query language for APIs and a runtime for fulfilling those queries with your existing data. It provides:

- a complete and understandable description of the data in your API,
- support for powerful developer tooling, and
- precise querying, which offers several benefits:
  - clients request only the data they need, improving efficiency;
  - new fields and features can be added without impacting existing clients; and
  - field-level usage can be tracked and monitored for insights and optimization.

The [GraphQL Specification](https://spec.graphql.org/) is open source and governed by the [GraphQL Foundation](https://foundation.graphql.org/).

## Documentation

- [GraphQL Website](https://graphql.org/)
- [Reference Documentation](https://graphql.org/learn/)
- [Language Support, Tools, and Services](https://graphql.org/code/)
- [Frequently Asked Questions (FAQ)](https://graphql.org/faq/)
- [Community Resources](https://graphql.org/community/)

## Deployment

The website is deployed via [Vercel](https://vercel.com) on merges to the `source` branch. To preview changes locally, follow these steps:

1. Clone the repository:  
   `git clone https://github.com/graphql/graphql.github.io.git`  
   `cd graphql.github.io`
2. Install dependencies:  
   `npm install`
3. Run the site locally:  
   `npm run dev`

## How to Contribute

We welcome contributions! 🎉 Please refer to our [contributing guide](./CONTRIBUTING.md) for detailed instructions on how to make changes to the GraphQL website.

### CLA Process

Before contributing, all participants must sign the free [GraphQL Specification Membership Agreement](https://preview-spec-membership.graphql.org). You only need to do this once, and it can be signed by:

- [Individual contributors](http://individual-spec-membership.graphql.org/)
- [Employers](http://corporate-spec-membership.graphql.org/)

To initiate the signature process, please open a PR against this repository. The EasyCLA bot will block the merge if the membership agreement has not been signed.

For more information on the CLA, check out the [detailed instructions here](https://github.com/graphql/graphql-wg/tree/main/membership). If you encounter any issues, please contact us at [operations@graphql.org](mailto:operations@graphql.org).

## Join the Foundation!

If your company benefits from GraphQL and you would like to provide essential financial support for the systems and people that power our community, please consider becoming a member of the [GraphQL Foundation](https://foundation.graphql.org/join).
