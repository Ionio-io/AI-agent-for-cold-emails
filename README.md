# AI agent for inbox management and cold emails

An autonomous agent created using [Langchain](https://www.langchain.com/) to automate your code review workflow for [smartlead](https://smartlead.ai/) campaigns

### [Read the blog!](https://www.ionio.ai/blog/how-to-create-an-ai-agent-to-manage-your-email-inbox-and-reply-to-your-cold-email-code-included)

## 🤔 How it works?

### 1. Get the Leads and Prepare Knowledge Base

It first takes your past emails and replies and generates its own knowledge base to refer while generating a response for any message so that it can write in your tone.

### 2. Classify Emails in different categories

From the given conversation history, it can classify your emails in different categories

### 3. Get Information about Lead

To add more human touch to your emails, it gets information about lead and their organization and adds part of it in your email reply

### 4. Replies to Your Emails in Your Tone and Writing Style

The agent will apply semantic search on your past email and replies and will generate new response based on that. Then it will use smartlead API to reply back to lead

## ⚒️ Architecture

![](https://assets-global.website-files.com/62528d398a42420e66390ef9/660a939de4d61c5b8ee00335_image1.png)

## 🚀 Getting started

### Prerequisites

- Python and anaconda installed on your machine
- OpenAI API Key
- Apollo API Key
- Smartlead API Key

### How to run?

- Clone the repository
- Create a file called `constants.py` in same folder and store all of your api keys like this

```
OPENAI_API_KEY = <key_here>
APOLLO_API_KEY = <key_here>
SMARTLEAD_API_KEY = <key_here>
```

- Open any jupyter notebook from repository and import the `constants.py` file in it
- Select your existing python environment or create one using anaconda
- Run the code
