# README.md

## Project Title: Postgres Chatbot with Streamlit

### Introduction

This project aims to develop a chatbot that can interact with a PostgreSQL database and answer queries in natural language. The chatbot will be able to handle queries related to an `Orders` table, which includes columns such as `order_id`, `customer_email`, `tracking_number`, `shipping_service`, `tracking_URL`, `order_created_at`, and `order_shipped_at`.

The chatbot will be designed to understand and respond to layman language questions, such as:
1. "Give me the status of order number 12222."
2. "What is the order ID of tracking number?"
3. "How many orders are shipped?"

A user interface will be created using Streamlit where users can input their PostgreSQL credentials and ask questions.

### Notes

- Questions will not be limited to one table, so it should be done to ask from database
- As long as entry is added into database, we should be able to answer questions for that new record
