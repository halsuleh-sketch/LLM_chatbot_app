python3.11 -m pip install transformers==4.38.2
python3.11 -m pip install torch==2.2.1


python3.11 -m pip install flask
python3.11 -m pip install flask_cors


python3.12 -m venv myenv
myenv\Scripts\activate  # On Windows


convert the prompt to windows

Invoke-WebRequest -Uri "http://127.0.0.1:5000/chatbot" `
  -Method POST `
  -ContentType "application/json" `
  -Body '{"prompt":"Hello, how are you today?"}'



Integrating your Chatbot into a Web Interface
https://editor.skills.network/render/?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhZG1pbiI6ZmFsc2UsImxhYiI6eyJpZCI6MCwibmFtZSI6IiIsInRvb2xfdHlwZSI6InRoZWlhIn0sInZlcnNpb24iOnsiaWQiOjB9LCJhdXRob3IiOnsiZW1haWwiOiIifSwibWRfdXJsIjoiaHR0cHM6Ly9jZi1jb3Vyc2VzLWRhdGEuczMudXMuY2xvdWQtb2JqZWN0LXN0b3JhZ2UuYXBwZG9tYWluLmNsb3VkL0lCTVNraWxsc05ldHdvcmstR1BYWDA0RVNFTi9sYWJzL2xhYjItbmV3Lm1kP3Q9MTc3NjQzMDY3MCIsImlhdCI6MTc3NjQzMDY3MSwiZXhwIjoxNzc2NDM0MjcxfQ.5Dl9HH8IpIOlhdKILkg1hSrPrYZlsOxNw8pa3WEwVOw

Create Simple Chatbot with Open Source LLMs using Python and Hugging Face
https://editor.skills.network/render/?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhZG1pbiI6ZmFsc2UsImxhYiI6eyJpZCI6MCwibmFtZSI6IiIsInRvb2xfdHlwZSI6InRoZWlhIn0sInZlcnNpb24iOnsiaWQiOjB9LCJhdXRob3IiOnsiZW1haWwiOiIifSwibWRfdXJsIjoiaHR0cHM6Ly9jZi1jb3Vyc2VzLWRhdGEuczMudXMuY2xvdWQtb2JqZWN0LXN0b3JhZ2UuYXBwZG9tYWluLmNsb3VkL0lCTVNraWxsc05ldHdvcmstQUkwMzMxRU4tU2tpbGxzTmV0d29yay9sYWJzL0Nsb3VkSURFXy1fQ3JlYXRlX0NoYXRHUFQtbGlrZV9XZWJzaXRlX3dpdGhfT3Blbl9Tb3VyY2VfTExNcy5tZD90PTE3NzgxNjA2MzkiLCJpYXQiOjE3NzgxNjA2MzksImV4cCI6MTc3ODE2NDIzOX0.peiYgNwmP9ST1y6Np77IQrWmpEqAs-idK4a4GDKhIjI

Congratulations! You have completed this module. At this point in the course, you know:

Chatbot is a computer program that simulates written or spoken human conversation.

With the integration of generative AI technology such as natural language processing, or NLP, chatbots can understand questions and respond based on the data they have collected.

A special program called a ‘transformer’ acts as the brain of the chatbot.

The transformer comprises a large language model, or LLM, that helps the chatbot understand the input question and generate the human-like response as the output.

To build the chatbot, you must select an LLM based on the chatbot’s purpose. Other important parameters for choosing an LLM include licensing, model size, training data, and performance and accuracy.

Transformers and LLMs work together within a chatbot to enable conversation.

In a chatbot application, the back-end server will receive the prompts from the front-end interface and feed them to the chatbot, which will process the prompts.

In this project, you worked on creating a simple chatbot using Facebook’s Blenderbot model and Hugging Face’s Python library, Transformers. Next, you learned to integrate the terminal chatbot into a web interface. You learned to host the back-end server using Flask.


