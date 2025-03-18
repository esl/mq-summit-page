---
tags: 
  - AI
  - OTP
  - LLM
level: Introductory and overview
title: "Utilizing LLMs in OTP applications"
speakers: -_participants/sebastian-goettschkes.md

---
Adding an LLM like GPT or Gemini might seem like integrating any other REST API on first glance. But these kind of APIs pose unique challenges! Responses might differ widely from one request to the next. Streams need specific formats for the application to be able to get all the relevant data and forward the stream to a client. Version changes between LLM models might cause the responses to change in unexpected ways. Automatic testing is error prone and can get expensive. And what to do with those restrictive rate limits? 

We will explore the general concepts of integrating LLMs into an Elixir application and then find answers to all the challenges mentioned above.

**Key Takeaways:**
- The general concept of how to integrate LLM APIs into an application;
- How to create and test prompts manually;
- Ways for utilizing streams from an LLM with custom formats;
- What to look out for when changing models;
- How to write automated tests for LLM APIs.

**Target Audience:**
- Software developers not yet familiar with LLM integrations

