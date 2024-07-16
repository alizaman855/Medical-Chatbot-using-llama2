---
title: "Medical Chatbot Using LLama2"
author: "Muhammad Zaman Ali"
date: "`r Sys.Date()`"
output: html_document
---

# 🚀 Introduction

Welcome to the AI Anytime Channel! In this project, we will develop a **medical chatbot** using the **LLama2 model**. LLama2 was released by Meta AI last week, and the open-source community has worked on quantization to make it available on compute-limited devices like a CPU machine.

# 🛠️ Tools and Technologies

This project leverages several tools and technologies to build an effective and efficient medical chatbot:

## 🦙 LLama2 Model

LLama2 is a powerful language model developed by Meta AI. It has been quantized by the open-source community to run efficiently on CPU machines, making it accessible for those without high-end GPUs.

## 📚 LangChain

LangChain is a framework designed to help you develop applications powered by language models. It handles the heavy lifting of integrating with different models, managing data processing, and more.

## 📝 Chainlit

Chainlit is an open-source Python package that provides an easy way to create conversational interfaces. It allows you to build chatbots with a user-friendly interface, similar to ChatGPT.

## 📄 PyPDFLoader

PyPDFLoader is a tool used to load PDF documents. It helps in extracting text data from PDF files, which is essential for creating the knowledge base for the chatbot.

## 🔄 RecursiveCharacterTextSplitter

This tool is used to split text into manageable chunks. It ensures that the text is split at logical points, preserving the meaning and context.

## 🧠 HuggingFace Embeddings

HuggingFace Embeddings are used to convert text data into numerical vectors. These vectors are then stored in a vector database for efficient retrieval during the chatbot's operation.

## 📊 FAISS

FAISS (Facebook AI Similarity Search) is a library for efficient similarity search and clustering of dense vectors. It is used to store and retrieve embeddings quickly.

# 📁 Project Structure

The project has the following structure:

