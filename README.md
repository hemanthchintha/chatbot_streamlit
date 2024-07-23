# gpt-assistants-api-ui

* 💬 OpenAI Assistants API chat 
* 🛠️ It works easily by setting the ASSISTANT IDs
* 📁 Supports file upload and file download
* 🏃 Supports Streaming API
* 👥 Supports multiple Assistant profiles in one place


4. 📦 Install dependencies

    ```bash
    $ poetry install
    ```

5. ⚙️ Set environment variables file `.env`

    ```bash
    # OpenAI settings
    OPENAI_API_KEY="sk-xxx"
    APP_ENABLED_FILE_UPLOAD_MESSAGE="Upload a file" # Leave empty to disable

    AUTHENTICATION_REQUIRED="False" # Must change to True if you require authentication

    # When using only one assistant, set the following, unset the OPENAI_ASSISTANTS variable.
    ASSISTANT_ID="asst_xxx"
    ASSISTANT_TITLE="Assistants API UI" # This is for the single agent title




