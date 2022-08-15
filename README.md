To execture this role-playing game. You have to prepare the following things:
1. Create your virtual environment
2. pip install parlai
3. Replace the worlds.py in ~/parlai/chat_service/tasks/chatbot with the world.py we privided.
4. Replace the client.py in ~/parlai/chat_service/services/terminal_chat with the client.py we provided
5. Replace the run.py in ~/parlai/chat_service/services/terminal_chat with the run.py we provided.
6. Download the retrival model: https://drive.google.com/drive/folders/1-IVulQ4SdIb5CeV85L3ZWZoGNOvUywhz?usp=sharing
7. Download the generative model: https://drive.google.com/drive/folders/1zzkxRKX-bcUz6pHGK4-9FfBpl9-6AQjM?usp=sharing
8. modify config.yml we provided with your own path of the model file.
9. run: python ~/parlai/chat_service/services/terminal_chat/run.py --config-path /path/to/config.yml
10. run: python ~/parlai/chat_service/services/terminal_chat/client.py

In this way, you can use this role-playing game on your PC
