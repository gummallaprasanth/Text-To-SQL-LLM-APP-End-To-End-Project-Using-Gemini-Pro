# Text-To-SQL LLM App (End-to-End) Using Gemini Pro

## Overview

This project demonstrates an end-to-end application that converts natural language queries into SQL statements using the Gemini Pro language model. The application allows users to interact with databases more intuitively, enabling them to retrieve data without needing extensive knowledge of SQL.

## Features

Natural Language Processing: Convert text queries into SQL queries.

Database Interaction: Execute generated SQL queries against a specified database.

User-Friendly Interface: Simple web interface for user interaction.

Customizable: Easily adapt to different databases and query requirements.

## Prerequisites

Python 3.9+

Streamlit(for frontend)

A compatible database (e.g., PostgreSQL, MySQL)

Gemini Pro API Key (required)

## Steps Involved In The Project:

1.Create a Simple data base using the sqlite3.
  
2.Then creating the app.py
  
  a.Create function for coverting the natural language  text into SQL queries.

  b.Use the converted SQL queries and retrive the data from the SQL data base.

## Example Queries

"Show me all users who registered last month."

"What are the total sales for this year?"

"List the top marks scored students."

"list the name of the students"

## Acknowledgments

Gemini Pro for the powerful language model.

Streamlit for the backend framework.

## Deployment:

This project can be deployed on various platforms like Heroku, AWS, Google Cloud Platform, or any other cloud hosting service that supports Python and Streamlit applications.
