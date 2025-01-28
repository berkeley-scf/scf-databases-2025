---
author: Christopher Paciorek
layout: default
title: 'Databases and SQL workshop'
---

# Logistics

Time: Saturday February 1, 9-3:30

Place: Evans 330

**Note: Evans is accessed by keycard on the weekends. If you don't have keycard access, email Chris and we'll arrange for you to be let in.**

# 1 Preparation

## 1.1 Required

- If you'd like to use Python, install either the `sqlite3` and/or `duckdb` packages on your laptop.
- If you'd like to use R, install the `RSQLite` and/or the `duckdb` packages on your laptop.
- Download [this SQLite database file](http://www.stat.berkeley.edu/share/paciorek/stackoverflow-2021.db) and/or [this DuckDB database file](http://www.stat.berkeley.edu/share/paciorek/stackoverflow-2021.duckdb) onto your laptop (or to your SCF account if you prefer to use SCF machines). (Note that if you happen to have problems with the original DuckDB database file, you can try [this alternative DuckDB database file](http://www.stat.berkeley.edu/share/paciorek/stackoverflow-2021-oldv.duckdb).
- Make sure you're able to access the SQLite or DuckDB version of the  database (or both) on your computer (or the SCF) using either [this R code](https://computing.stat.berkeley.edu/tutorial-databases/#61-using-sql-from-r) or [this Python code](https://computing.stat.berkeley.edu/tutorial-databases/#62-using-sql-from-python).

Alternatively, if you have an SCF account, you can plan to use one of the SCF machines via ssh or the [SCF Jupyterhub](jupyter.stat.berkeley.edu). You should still make sure you are able to access the database (SQLite or DuckDB) using either R or Python.

## 1.2 Recommended

It would be helpful if you had an account (a free plan is fine) with a ChatBot service such as ChatGPT, Claude, or the like. You can also try to use [Chatbot Arena](lmarena.ai).

# 2 (Approximate) Schedule 

- 9 am - 10 am: (Optional Session 1) review/introduction to databases, database schema and normalization, and very basic SQL syntax
- 10 am - noon: (Session 2) grouping, joins, set operations, subqueries, practice problems
- noon - 1:15 pm: lunch (on your own)
- 1:15 pm - 3:30 pm: (Session 3) window functions, advanced practice problems, including use of Chatbot/LLM assistance

# 3 Material

The tabs at the top will guide us through the material to be covered in the workshop. We'll be accessing the background material in the [SCF Databases tutorial](https://berkeley-scf.github.io/tutorial-databases), interspersed with time to work on SQL practice problems.
