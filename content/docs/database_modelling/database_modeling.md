---
weight: 3
title: "Database Modeling"
description: ""
icon: "article"
date: "2024-04-08T22:35:11-03:00"
lastmod: "2024-04-08T22:35:11-03:00"
draft: false
toc: true
---

## User

- id: int
- name
- date_created
- last_logged_in

## Action

- id
- name
- description
- user_id (FK)
- label_id (FK)
- context_id (FK)

## Label

- id

## Project

- id

## Attachment

- id: int
- file: bytes

## Log

- id: int
- description
- datetime
