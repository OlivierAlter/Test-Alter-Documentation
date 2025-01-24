

# <a id="getting-started">Getting Started</a>

## <a id="invoking-alter">Invoking Alter</a>

### The Notch

Hover your mouse over the notch to open Alter.

![Open_notch](https://hackmd.io/_uploads/rkBSeIydJg.gif)


> On an external screen, you can hover anywhere except on the mic to open Alter.

### Hotkey - Alter Quick Menu

Press your Alter Quick Menu shortcut to open Alter from anywhere.

> You can configure the Alter Quick Menu in **Settings > Shortcuts** (LINK TO PUT).

### Voice Command

#### Quick Prompt
Hold the mic icon to speak on your notch or use your speech-to-text hotkey to start a quick prompt using your voice.

![Click_mic](https://hackmd.io/_uploads/ry2fML1dJe.gif)


> You can configure the speech-to-text hotkey in **Settings > Default**.

#### Dictate
Click once on the mic icon on your notch to dictate a prompt, and click again to finish dictation.

![Click_mic](https://s13.gifyu.com/images/SeQGe.gif)


> The transcript of your recording is visible in the context of Alter.

#### Mouse Interaction

##### Text Selection
Select text anywhere to invoke the Alter Floating Menu.

> The Alter Floating Menu only shows the system's Alter actions.  
> Favorite system Alter actions will appear at the top of the menu instead of in their respective folders.

##### Right-Click
Right-click on a file or folder, then select **Add to Alter** to send it to Alter.

![Right Click](https://s13.gifyu.com/images/SeWzU.gif)



## Chosing your language
TBC
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

## Core Features

### Interacting with Your Apps

#### Appsense - Understanding Your Mac

Alter leverages your screen's content to offer a better experience and unlock new possibilities.

##### Current Application

Alter will automatically suggest using the active window as context.  
Click **Active Window Selection** below the prompt, or press **Arrow Down** and **Enter**.

![App Sense](https://s7.gifyu.com/images/SeWv0.gif)

##### Other Applications

TBC

### Interacting with Files and Folders

You can add files to Alter as context.

##### Drag-and-Drop Support

Drag and drop files or folders onto Alter's notch icon, or use **Right Click > Add to Alter**.

![Drag'n'drop](https://s13.gifyu.com/images/SeWLX.gif)

##### Supported File Types

1. **Document Files**: `.xlsx`, `.docx`, `.pdf`, `.txt`, `.md`, `.org`, `.rtf`.  
2. **Image Files**: `.jpg`, `.png`, `.heic`, `.gif`, `.tiff`, `.svg`.  
3. **Web Content**: `.html`, URLs, dragged text.  
4. **Email Content**: `.eml`, Apple Mail messages.  
5. **Audio Files**: `.mp3`, `.wav`, `.m4a`, `.aac`, `.flac`.  
6. **Code Files**: Common programming languages, configuration, shell scripts.  
7. **Special Handling**: Directory drops, OCR for images and PDFs, text encoding detection.

> When dropping an image file, use a model with vision capability.  

##### Audio files and transcript

When adding  an audio file, you need to generate the transcript manually.

NEED VIDEO HOSTING
![Transcirpt audio](https://s7.gifyu.com/images/SeWuj.gif)


> If you drop a video file in Alter, we will extract the audio track, and try to transcribe it. It may or may not work, as it is a unsupported feature :)


### Workspaces

A workspace is a collection of files and folders grouped for easy access in Alter.

NEED VIDEO HOSTING
![Transcirpt audio](https://s13.gifyu.com/images/SeWiq.gif)

- **Create**: In your context window, drag and drop multiple files together .  
- **Rename**: Double-click the workspace to edit the title.  

> Adding folders to a workspace enables automatic monitoring and indexing of new files.

### Interacting with a YouTube video

When visiting a YouTube video page:  
- Alter will notify you with an option to summarize the video.  
- The video's transcript will be added to your context window, even if you ignore the notification 

> This works only if the Youtube video has a transcribe available

### Recording Meetings

During online calls, Alter suggests recording via a subtle notification.  

![Transcirpt audio](https://s13.gifyu.com/images/SeWr0.gif)


#### Manually start the recording:
- Start recording by clicking the mic icon on the notch. It will turn into a red recording button  
- End recording by clicking the red button.

> The mic will animate during transcription

![Manual meeting recording](https://s7.gifyu.com/images/SeWP9.gif)

(CHECK LATER THE TRANCRIPTs WORKFLOW)

> You can find your recordings and your transcripts in `~/Library/Application Support/Alter/Transcripts`

### Alter Actions - Workflows

#### General Principle

Alter Actions are advanced prompts configured with triggers and instructions.  
Default actions are organized in folders.

#### Create Your Actions

You can create actions via:  
- **Action Editor**: Accessible from the menu bar.  
- **Prompt Box**: Invoke "Create > Alter Action" and specify your requirements.

> Built-in actions cannot be edited but can be duplicated.