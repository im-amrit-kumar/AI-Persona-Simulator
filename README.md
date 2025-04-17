🎭 AI Persona Simulator – Chat with Tech Legends! 🤖💬

The AI Persona Simulator is a creative Python-based application that enables users to chat with simulated versions of famous tech personalities such as Elon Musk, Sundar Pichai, and others using Cohere’s Generate API. The project focuses on replicating the tone, style, and thought patterns of selected personas through customized prompts and a responsive GUI.

It’s a perfect blend of natural language processing, user interface design, and creative prompt engineering, built with accessibility and ease-of-use in mind.

📌 Features

✅ Persona Simulation

Injects role-specific context (like background, speech style, values, and domain knowledge) into each prompt to realistically simulate famous tech personas.

✅ Multi-Turn Chat Support

Preserves context and conversation history, enabling natural and logical back-and-forth communication with the selected persona.

✅ GUI Built with Tkinter

A simple and user-friendly interface allows users to choose a persona, type their query, and receive intelligent replies with real-time updates.

✅ Custom System Prompting

Each persona is initialized with a unique system prompt that defines their behavior, language style, expertise, and even temperament (e.g., Elon Musk speaks boldly and futuristically).

✅ Thread-Safe API Calls

Uses threading and avoids asyncio.run() in running event loops to maintain smooth performance and prevent runtime errors during GUI interaction.

✅ Easy Persona Extension

New personas can be added by simply updating a dictionary with their name, description, and prompt structure.



📂 Requirements

🔸 A working Cohere API Key (you can get one from https://cohere.com)

🔸 A Python environment with the following libraries:


Python Libraries:

cohere – For accessing Cohere's large language model

tkinter – To create the interactive GUI

threading – To execute API calls without freezing the GUI

asyncio – For managing async calls in background

queue – For thread-safe communication between functions



🛠️ Tech Stack

Component	Purpose

Python 3.x	Core programming language

Cohere API	Backend LLM service for text generation

Tkinter	GUI library for user interaction

Threading	Keeps UI responsive during API calls

Asyncio	Async-safe prompt execution


🧠 How It Works

Select Persona

Choose from a dropdown list of tech personalities (e.g., Elon Musk, Sundar Pichai).


Enter a Message

Type your query or conversation message into the text input box.

Persona Responds

The app sends a structured prompt to the Cohere model using the selected persona’s style and tone, and returns a realistic simulated reply.

Continue Conversation

The chat history updates with each exchange, maintaining context to simulate real-time dialogue.


🚀 How to Run

Step 1: Install Dependencies

pip install cohere

Step 2: Open Notebook

Launch the .ipynb file in Jupyter Notebook or convert it into a .py file if you want a standalone GUI experience.

Step 3: Add Your API Key

Paste your Cohere API key in the specified input field or code cell.

Step 4: Run the GUI

Execute the final cell to launch the Tkinter-based simulator.

Step 5: Chat Away!

Choose your persona

Ask your questions

Get simulated answers with engaging and realistic tones



👨‍💻 Example Personas

Persona	Behavior Style

Elon Musk	Bold, futuristic, visionary, quirky

Sundar Pichai	Calm, analytical, product-focused

Steve Jobs	Charismatic, visionary, perfectionist

(Add more easily by editing the persona dictionary)	
