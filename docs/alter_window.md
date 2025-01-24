## The Alter Window

### General Concept

The Alter window is your gateway to improving productivity.  
It is divided into three main sections:

1. **Context**
2. **Prompt**
3. **Additional Selection**

You can interact within the Alter window using a mouse or keyboard keys:
- Use **Up, Down, Left, Right** to navigate between objects.
- Press **Enter** to select an object.

> See the **Prompt Box** section for details on manipulating it using keyboard keys.


### The Context Section

The **Context** section displays elements sent to Alter for reference. These can include:
- Files
- Folders
- Windows
- Transcripts
- Workspaces

You can send multiple context elements to Alter and mix different types.

### The Prompt Box

The **Prompt Box** is where the magic happens.  
Start typing your prompt or an Alter Action title to send it to your LLM model.

> To invoke an Alter Action, type any character in its title.  

- Use **Enter** to use your default model.  
- Use **CMD+Enter** to perform a web search (via Perplexity).
    - Use **Option+Enter** to do a line break.

Prompt Box shortcuts:
- **@**: Add elements to the context.  
- **#**: Add previous prompt responses to the current context.  
- **?**: Show the help menu.

### Additional Context Selections

This section lets you add more elements to your context.

> The list of additional context selections adapts based on your current context. Learn more by reading (LINK TO PUT).

## Choosing Your Generative Model

By default, Alter offers a variety of models, listed alphabetically by their hosting company.  

When using your API key or a local model, these appear at the top under **Custom**.  
All other interactions are routed through Alter Cloud.

> To view all available models, visit (LINK TO PUT).

### Via Alter Cloud

By default, you connect to models via Alter Cloud.
The default model is **Claude-3.5-Sonnet-Latest**.

> (PUT SOMETHING ABOUT CREDITS)  

You can change the default model in **Settings > Defaults > Model**.  
> To view all available models, visit (LINK TO PUT).

### Via Your API Key

You can use your own API key to connect directly to your provider's endpoint:  
1. Go to **Settings > Defaults > Custom Endpoint**.  
2. Set:
   - **Endpoint URL**: Enter the endpoint URL.
   - **Endpoint API Key**: Enter your API key.

> Once connected, a tick will appear next to **Custom Endpoint**.  

Your provider's models will be listed under the **Custom** section.

### Locally via Ollama or StudioLM

![Custom Local](https://s7.gifyu.com/images/SeW9i.png)

To use Alter with local models (via Ollama or StudioLM):  
1. Go to **Settings > Defaults > Custom Endpoint**.  
2. Set:
   - **Endpoint URL**: Enter your Ollama or StudioLM server URL.

For local servers, the default URLs are:  
- Ollama: `http://127.0.0.1:11434`  
- StudioLM: `http://127.0.0.1:1234`

> Once connected, a tick will appear next to **Custom Endpoint**.  

Your local models will be listed under the **Custom** section.

![Custom model](https://s7.gifyu.com/images/SeWE4.png)