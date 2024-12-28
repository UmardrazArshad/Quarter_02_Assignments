# Assignment-01
## **Understanding OpenAI Chat Completion API Parameters**

## 1. Messages

**Definition:**  Messages refer to the conversation history exchanged between the user and the AI. \
This includes the user's inputs and the AI's responses.\
**Purpose:** The API uses these messages to maintain the context of the conversation.

**Example:**\
    messages = [
    {"role": "system", "content": "You are a helpful assistant."}, \
    {"role": "user", "content": "What is AI?"},\
    {"role": "assistant", "content": "AI stands for Artificial Intelligence."}\
]

Here, the system sets the assistant's tone, and the rest are user-assistant interactions.

## 2. Model
 
**Definition:**  This parameter specifies which AI model to use for generating responses.\
**Purpose:**  Different models offer varying levels of capability, speed, and cost.\
**Example:**  Models like gpt-4 (advanced, slower) or gpt-3.5-turbo (faster, cost-effective) can be chosen based on requirements.

## 3. Max Completion Tokens

**Definition:**  This limits the maximum number of tokens (words or pieces of words) the AI can use in its response.\
**Purpose:**  It ensures the response doesn't exceed a specific length.\
**Example:**  If set to 50, the AI will generate up to 50 tokens in its response.

## 4. n

**Definition:**  Determines how many response completions the API should generate.\
**Purpose:**  Useful for exploring multiple variations of a response.\
**Example:**  If n=3, the API will return 3 different completions for the same prompt.

## 5. Stream

**Definition:**  When enabled (True), the response is sent back in chunks (streamed) instead of waiting for the complete response.\
**Purpose:**  Provides a real-time experience, ideal for chat applications.\
**Example:**  In a live chat, the user can see the assistant typing in real-time.

## 6. Temperature

**Definition:** Controls the randomness of the response, ranging from 0 to 1.\
**Purpose:**
Lower values (e.g., 0.2) make responses more deterministic and focused.
Higher values (e.g., 0.8) make responses more creative.\
**Example:** For factual queries, use a low temperature. For creative writing, use a high temperature.


## 7. Top_p

**Definition:**  This is an alternative to temperature that uses nucleus sampling.\
**Purpose:**  Limits the AI to consider only the most probable tokens until their cumulative probability reaches p.\
**Example:**  If top_p=0.9, only the top 90% of probable words are considered, adding diversity while maintaining relevance.


## 8. Tools

**Definition:**  Refers to any external functionalities or APIs integrated with the Chat Completion API.\
**Purpose:**  Enhances the AI’s ability by connecting it to tools like calculators, databases, or custom APIs.\
**Example:**  A tool integration could allow the AI to perform mathematical calculations or fetch live data.

