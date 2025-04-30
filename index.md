---
layout: default
title: AI Agent Recipes 
---

# AI Recipes for Better Coding Agents

Welcome to the AI Agent Instructions repository. This site provides examples of workable instructions to constrain your AI agent to modern software engineering practices.

## Available Instructions

{% assign sorted_pages = site.pages | sort: 'title' %}
{% for page in sorted_pages %}
{% if page.title and page.url != "/" and page.url != "/404.html" %}
- [{{ page.title }}]({{ page.url | relative_url }})
{% endif %}
{% endfor %}

## Purpose

This collection aims to help developers create more effective prompts for AI coding assistants, ensuring they follow best practices in software development.

Feel free to use these instructions in your own projects when working with AI coding agents.
