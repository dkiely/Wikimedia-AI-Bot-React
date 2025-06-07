# Wikimedia-AI-Bot-React

This AI bot will allow users to ask questions, and it will use the power of the Gemini AI model in conjunction with the Wikimedia API to find information and provide concise answers.

The application is a React-based web application. It will feature a simple chat interface where you can type your questions. When you send a message, the bot will perform the following steps:

 - It will first search Wikipedia for articles related to your query.
 - If an article is found, it will fetch a summary of that article.
 - Finally, it will send your original question along with the Wikipedia summary to the Gemini AI model, which will then generate a concise and relevant answer.

This demonstrates how to integrate large language models (LLMs) with external data sources to create more informed and helpful AI agents.

The bot provides a user-friendly chat interface for querying information. It first searches Wikimedia for relevant articles, then uses the Gemini AI model to process the retrieved information and deliver a concise answer. This makes it a powerful tool for quickly getting summarized information from a vast knowledge base.
