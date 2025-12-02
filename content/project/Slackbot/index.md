---
title: Designing a Slackbot for Internal Whatfix Feedback Collection  
date: 2025-08-29  
toc: false  
tags:  
summary: Planned a Slackbot to streamline incoming feedback for high-visibility Whatfix content, including sample flows and JSON structure  
---

## Overview  
As part of ongoing improvements to our Whatfix help content and release communication, I designed a Slackbot workflow to **streamline stakeholder feedback collection**. Although development was paused due to resource constraints, I fully mapped out the logic and structure (including sample Slackbot JSON blocks and a logic spreadsheet) so the idea could be implemented when resourcing allows.

## 🧩 The Problem  
With plans underway to publish release notes for Whatfix content, I anticipated a surge in feedback, questions, and suggestions from across the organization. Without a single intake mechanism, this feedback risked becoming fragmented across Slack DMs, email threads, and one-off conversations.  

I needed a **simple, centralized way** for stakeholders to provide input, ideally one that integrated cleanly into both the release notes and our Jira system.

## 💡 My Solution  
I proposed a **Slackbot feedback form** that could be linked directly from release notes. The bot would walk users through structured questions and then auto-generate a Jira ticket.

Key features of my design included:

- Clear prompts for product, content type, and issue description  
- Conditional blocks based on user input
- Auto-routing logic to map responses to appropriate Jira projects  
- Final confirmation message with a ticket link  
- Complete Slackbot block logic laid out in a structured spreadsheet  
- Sample JSON files prepared to guide eventual development

This approach would help the team:
- **Consolidate communication** through a single, trackable channel  
- **Streamline triage** by collecting all necessary context upfront  
- **Maintain visibility** of feedback for the broader team

## 📄 Design Files  
- [Slackbot Logic Spreadsheet (Planning Doc)](https://docs.google.com/spreadsheets/d/1V-mjC_S_cpD81JbDW0rP3w590tUcHZYk/edit?usp=sharing&ouid=112942925481969310177&rtpof=true&sd=true)  
- [Block JSON Files (Zipped)](https://drive.google.com/file/d/1sS0Zky24XoyJWknKR3kZ5tWOZoHKE8is/view?usp=sharing)  


## 🔁 Status  
Although the Slackbot has not yet been implemented due to developer bandwidth, the logic, assets, and intent have been shared and are ready to go when resourcing is available. This project shows my ability to **think ahead**, **plan scalable systems**, and **create developer-ready artifacts** in cross-functional environments.
