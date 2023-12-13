# Learn-with-a-bot
The language learning application harnesses OpenAI's capabilities to offer tailored and interactive lessons for mastering new languages.

## Step to run
Step 1: Setting Up OpenAI Keys in config.json

Rename the config-template.json file to config.json.

Within config.json, locate the fields for OpenAI keys (OPENAI_API_KEY and OPENAI_API_ID).

Insert your specific OpenAI API key and API ID into their respective fields within the config.json file.

Example config.json:


``` Json
{
  "OPENAI_API_KEY": "your_openai_api_key",
  "OPENAI_API_ID": "your_openai_api_id"
}
```

Ensure that you replace "your_openai_api_key" and "your_openai_api_id" with the actual API key and ID provided by OpenAI. This step enables proper authentication with OpenAI services within your application.