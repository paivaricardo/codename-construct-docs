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

## Database model

You can consult the data model through this [link](https://app.sqldbm.com/PostgreSQL/DatabaseExplorer/p295073/).

## Tables

### system_user

- system_user_id: number
- name: text
- email: text
- date_created: datetime
- last_logged_in: datetime

### action

- action_id: number
- name: text
- description: text:
- system_user_id (FK): number
- label_id (FK): number
- context_id (FK): number



### label

- label_id

### project

- project_id

### attachment

- attachment_id: int
- file: bytes

### log

- log_id: int
- description
- datetime
