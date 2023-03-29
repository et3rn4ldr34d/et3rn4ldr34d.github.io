---
layout: post
title: "Sources and Sinks"
date:   2023-02-24 00:44:28 -0700
categories: jekyll update
---
# **Sources and Sinks**

## What is it?

This is a concept that you take potentially harmful functions known as sinks and list them along with potentially vulnerable data sources known as sources, then you match up your sources with the sinks.

Essentially, this provides a top down or bottom up approach in order to exploit vulnerabilities.  When you start from your sources, you look for potentual ways to connect with one or multiple sinks.  When you know there is a sink, you can try to work backwards to link to a vulnerable data source.

## How do I look for it?

Parse or Regex through datasets, look for unencrypted data.  There are many tools that can help you with sorting data and as I come across them, I will post them.

It can be difficult to find the sources and sinks when you aren't too familiar with the stacks/languages used.  However, it's not impossible.  Look for some common points of attack on Google then go from there to build out your knowledge.

## How do I exploit it?

If you know that a function is a known risk, it makes sense that if you can trace a variable back to a vulnerable source, you can exploit the code, and it needs to be either sanitized or corrected.

## What is the impact?

Variable.

## How do I remidiate it?

Make sure you take the extra steps to secure your API keys and other sensitive data as part of your development environment.  Use the same tools on your own code to ensure security of sensitive sources.

## Where can I learn more?

[Semgrep](https://semgrep.dev/)
[Graudit](https://github.com/wireghoul/graudit)
[CodeQL](https://codeql.github.com/)