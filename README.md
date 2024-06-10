# Welcome to the Gemini API Cookbook
This is a collection of guides and examples for the Gemini API, including [quickstart](https://github.com/google-gemini/cookbook/tree/main/quickstarts) tutorials for writing prompts and using different features of the API, and [examples](https://github.com/google-gemini/cookbook/tree/main/examples) of things you can build.

## Get started with the Gemini API
The Gemini API gives you access to Gemini [models](https://ai.google.dev/models/gemini) created by [Google DeepMind](https://deepmind.google/technologies/gemini/#introduction). Gemini models are built from the ground up to be multimodal, so you can reason seamlessly across text, images, code, and audio. You can use these to develop a [range of applications](https://ai.google.dev/examples/).

### Start developing
1. Go to [Google AI Studio](https://aistudio.google.com/).
2. Login with your Google account.
3. [Create](https://aistudio.google.com/app/apikey) an API key.
4. Use a [quickstart](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Prompting.ipynb) for Python, or call the REST API [using curl](https://github.com/google-gemini/cookbook/blob/main/quickstarts/rest/Prompting_REST.ipynb).

## Table of contents
Learn about the capabilities of the Gemini API by checking out the quickstarts. These are tutorials that walk you through how to use a feature of the Gemini API with complete end to end code.
* [Authentication](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Authentication.ipynb): Start here to learn how you can set up your API key so you can get access to the Gemini API.
* [Counting Tokens](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Counting_Tokens.ipynb) Tokens are the basic inputs to the Gemini models. Through this notebook, you will gain a better understanding of tokens through an interactive experience.
* [Working with files](https://github.com/google-gemini/cookbook/blob/main/quickstarts/File_API.ipynb): Use the Gemini API to upload files (audio, video, images, code, text) and perform actions with them through the Gemini models.
* [Audio](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Audio.ipynb): Learn how to use the Gemini API with audio files.
* [JSON mode](https://github.com/google-gemini/cookbook/blob/main/quickstarts/JSON_mode.ipynb): Discover how to use JSON mode.
* [Function Calling](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Function_calling.ipynb): The Gemini API works great with code. Use this quickstart to learn how to write prompts to understand and call functions. Then check out the [function calling config](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Function_calling_config.ipynb) tutorial to learn more.
* [System Instructions](https://github.com/google-gemini/cookbook/blob/main/quickstarts/System_instructions.ipynb): Give models additional context on how to respond by setting system instructions.
* [Embeddings](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Embeddings.ipynb): Create high quality and task-specific embeddings.
* [Tuning](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Tuning.ipynb): Learn how to improve model performance on a specific task through tuning. 

Browse the [quickstarts folder](https://github.com/google-gemini/cookbook/tree/main/quickstarts) for more tutorials, and check out the [examples folder](https://github.com/google-gemini/cookbook/tree/main/examples) for more cool examples.  

## Official SDKs
The Gemini API is a REST API. You can call the API using a command line tool like `curl` (and you can find REST examples [here](https://github.com/google-gemini/cookbook/tree/main/quickstarts/rest)) , or by using one of our official SDKs:
* [Python](https://github.com/google/generative-ai-python) - Note: all the notebooks in this cookbook install the Python SDK for you.
* [Node.js](https://github.com/google/generative-ai-js)
* [Dart (Flutter)](https://github.com/google/generative-ai-dart)
* [Android](https://github.com/google/generative-ai-android)
* [Swift](https://github.com/google/generative-ai-swift)
* [Go](https://github.com/google/generative-ai-go)

## Get help
Ask a question on the new [Build with Google AI Forum](https://discuss.ai.google.dev/), or open an [issue](https://github.com/google-gemini/cookbook/issues) on GitHub.

## Contributing
Contributions are welcome. See [contributing](https://github.com/google-gemini/cookbook/blob/main/CONTRIBUTING.md) to learn more.

Thank you for developing with the Gemini API! We’re excited to see what you create.
