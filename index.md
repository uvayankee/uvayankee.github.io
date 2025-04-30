---
layout: default
title: AI Agent Instructions
---

# Specific AI Instructions for Coding Agents

Welcome to the AI Agent Instructions repository. This site provides examples of workable instructions to constrain your AI agent to modern software engineering practices.

## Available Instructions

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Purpose

This collection aims to help developers create more effective prompts for AI coding assistants, ensuring they follow best practices in software development.

Feel free to use these instructions in your own projects when working with AI coding agents.