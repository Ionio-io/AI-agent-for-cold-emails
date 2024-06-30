# AI agent for inbox management and cold emails

An autonomous agent created using [Langchain](https://www.langchain.com/) to automate your code review workflow for [smartlead](https://smartlead.ai/) campaigns

## Read the blog 👇

### [Blog Part 1](https://www.ionio.ai/blog/how-to-create-an-ai-agent-to-manage-your-email-inbox-and-reply-to-your-cold-email-code-included)

### [Blog Part 2](https://www.ionio.ai/blog/how-to-create-an-ai-agent-to-manage-your-email-inbox-and-reply-to-your-cold-email-code-included-part-2)

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

![image](https://github.com/Ionio-io/AI-agent-for-cold-emails/assets/70281451/63159a2f-931c-4646-a1ef-4863b163fc9e)

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
