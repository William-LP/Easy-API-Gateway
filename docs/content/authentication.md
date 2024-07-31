---
title: Authentication
weight: 2
draft: false
---

Parapluie uses two special token called the **Parapluie Root Token** and the **Consumer API Key**.

It is essential to distinguish between the Parapluie Root Token and a Consumer API key, as they serve different purposes and are used in different contexts. You will find [on this page](/how-it-works) a sequence datagram showing how those tokens work together.

## Parapluie Root Token

This token is provided for users to interact with Parapluie's API, allowing them to create and manage Parapluie resources such as rate limits or Consumer API keys. 

## Consumer API Key

A [Consumer API Key](/features/consumer-api-key) is a token that is used between a Consumer (a customer of you or your frontend application) and Parapluie. This Consumer API Key is then processed by Parapluie to understand if the query should be forwarded to your backend API.