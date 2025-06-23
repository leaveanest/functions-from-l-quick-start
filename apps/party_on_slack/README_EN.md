# Party on Slack Function List

## Table of Contents

- [Party on Slack Function List](#party-on-slack-function-list)
  - [Table of Contents](#table-of-contents)
  - [1. Initial Setup and Access Control](#1-initial-setup-and-access-control)
    - [1.1 App Installation](#11-app-installation)
    - [1.2 Global Lock Setting Function](#12-global-lock-setting-function)
    - [1.3 Workspace Permission Settings](#13-workspace-permission-settings)
  - [2. API Key Settings and Basic Authentication](#2-api-key-settings-and-basic-authentication)
    - [2.1 Registration and Verification of Various API Keys](#21-registration-and-verification-of-various-api-keys)
      - [API Key Registration and Verification](#api-key-registration-and-verification)
    - [2.2 Model Selection Function](#22-model-selection-function)
    - [2.3 Workspace Model Settings](#23-workspace-model-settings)
  - [3. Basic AI Chat Functions](#3-basic-ai-chat-functions)
    - [3.1 Mention Response in Channels](#31-mention-response-in-channels)
    - [3.2 DM Conversations](#32-dm-conversations)
    - [3.3 Continuous Conversation in Threads](#33-continuous-conversation-in-threads)
    - [3.4 Thread Model Change Function](#34-thread-model-change-function)
    - [3.5 Channel Model Change Function](#35-channel-model-change-function)
    - [3.6 Character Settings (System Prompt)](#36-character-settings-system-prompt)
  - [4. File Processing Functions](#4-file-processing-functions)
    - [4.1 File Summarization (Word, PPT, Excel, CSV)](#41-file-summarization-word-ppt-excel-csv)
    - [4.2 URL Summarization](#42-url-summarization)
    - [4.3 Image Recognition (Multimodal)](#43-image-recognition-multimodal)
    - [4.4 Audio File Transcription](#44-audio-file-transcription)
  - [5. Content Generation Functions](#5-content-generation-functions)
    - [5.1 Image Generation](#51-image-generation)
    - [5.2 Voice Generation](#52-voice-generation)
    - [5.3 Canvas Creation Function](#53-canvas-creation-function)
  - [6. Search and Integration Functions](#6-search-and-integration-functions)
    - [6.1 Web Search Function](#61-web-search-function)
    - [6.2 Ask Slack Function (Internal Search)](#62-ask-slack-function-internal-search)
    - [6.3 Ask Slack Function (Summary Feature)](#63-ask-slack-function-summary-feature)
    - [6.4 Pinecone Integration (Vector DB)](#64-pinecone-integration-vector-db)
    - [6.5 Google Spreadsheet RAG](#65-google-spreadsheet-rag)
  - [7. Translation Functions](#7-translation-functions)
    - [7.1 Stamp Translation Settings](#71-stamp-translation-settings)
    - [7.2 Translation Model Selection](#72-translation-model-selection)
    - [7.3 Translation Destination Settings (Thread/Channel)](#73-translation-destination-settings-threadchannel)
  - [8. Automation and Scheduled Execution Functions](#8-automation-and-scheduled-execution-functions)
    - [8.1 RSS Concierge](#81-rss-concierge)
    - [8.2 LLM Log Transfer](#82-llm-log-transfer)
  - [9. External Service Integration](#9-external-service-integration)
    - [9.1 Google Integration (Calendar Coordination)](#91-google-integration-calendar-coordination)

## 1. Initial Setup and Access Control

### 1.1 App Installation

1. Access https://lne.st/pt
2. Click the "Add to Slack" button
3. Select which workspace to install to
4. Review permissions and click the authorize button

[![App Installation](http://img.youtube.com/vi/ODa18XV4qj4/0.jpg)](https://youtu.be/ODa18XV4qj4)

### 1.2 Global Lock Setting Function

1. Open the home screen
2. Click the "Lock" button
3. Select the settings to lock
4. Click the "Lock" button
5. Confirm that other users cannot change the settings

[![Global Lock Setting Function](http://img.youtube.com/vi/pyEUES06y4U/0.jpg)](https://youtu.be/pyEUES06y4U)

### 1.3 Workspace Permission Settings

1. Open the home screen
2. Click the "Open" button in the "Workspace Permissions" section
3. Review permission settings for DM usage, multimodal, image generation, and voice generation
4. Select "Allow" or "Disallow" as needed

[![Workspace Permission Settings](http://img.youtube.com/vi/w-g0ItPHAaE/0.jpg)](https://youtu.be/w-g0ItPHAaE)

## 2. API Key Settings and Basic Authentication

### 2.1 Registration and Verification of Various API Keys

#### API Key Registration and Verification

1. Open the home screen
2. Click the "Settings" button in the "API Key Settings" section
3. Enter the API key you want to register in the input field
4. Click the "Save" button
5. Confirm that "API Key is registered" is displayed

[![API Key Registration and Verification](http://img.youtube.com/vi/8oZmn4Hrh2k/0.jpg)](https://youtu.be/8oZmn4Hrh2k)

### 2.2 Model Selection Function

1. Open the home screen
2. Click the "Settings" button in the "Model Selection" section
3. Check the models you want to use
4. Click the "Save" button
5. Confirm that only the selected models are displayed when selecting models in channels

[![Model Selection Function](http://img.youtube.com/vi/dgqPeUedz7E/0.jpg)](https://youtu.be/dgqPeUedz7E)

### 2.3 Workspace Model Settings

1. Open the home screen
2. Select a model from the dropdown "Please select the language model to use for chat"
3. Confirm that only the selected model is displayed when selecting models in channels

Models selected in channels take priority over models registered in the workspace.

[![Workspace Model Settings](http://img.youtube.com/vi/Gc9bOSykWcg/0.jpg)](https://youtu.be/Gc9bOSykWcg)

## 3. Basic AI Chat Functions

### 3.1 Mention Response in Channels

1. Open a channel where Party on Slack is participating
2. Mention @Party on Slack and enter a message
3. Send the message
4. Confirm that the AI's reply appears in a thread
5. Confirm that the thread menu is displayed

[![Mention Response in Channels](http://img.youtube.com/vi/2zJXFrQ2fss/0.jpg)](https://youtu.be/2zJXFrQ2fss)

### 3.2 DM Conversations

1. Select the "Party on Slack" app from the left sidebar
2. Click "New Chat"
3. Enter and send a message (no mention required)
4. Confirm that the AI's reply is displayed

[![DM Conversations](http://img.youtube.com/vi/3zqQgsPuywo/0.jpg)](https://youtu.be/3zqQgsPuywo)

### 3.3 Continuous Conversation in Threads

1. Open an existing conversation thread with the AI
2. Enter and send a new message
3. Confirm that the AI understands the context of the previous conversation and replies
4. Continue multiple exchanges and confirm that the conversation continues

[![Continuous Conversation in Threads](http://img.youtube.com/vi/N66LbMk-iXE/0.jpg)](https://youtu.be/N66LbMk-iXE)

### 3.4 Thread Model Change Function

1. Open a conversation thread with the AI
2. Click the model selection dropdown at the bottom of the thread menu
3. Select the model you want to use
4. Send a new message and confirm that the reply comes from the selected model

[![Thread Model Change Function](http://img.youtube.com/vi/5aU89c2bzi8/0.jpg)](https://youtu.be/5aU89c2bzi8)

### 3.5 Channel Model Change Function

1. Mention Party on Slack in a channel
2. Click the channel settings button in the thread menu
3. Select a model from the model selection dropdown
4. Click the "Set" button
5. Send a new message and confirm that the reply comes from the selected model

[![Channel Model Change Function](http://img.youtube.com/vi/aPZzMGaErSI/0.jpg)](https://youtu.be/aPZzMGaErSI)

### 3.6 Character Settings (System Prompt)

1. Mention Party on Slack in a channel
2. Click the channel settings button in the thread menu
3. Click the character settings button
4. Enter character settings in the character settings text area
5. Click the "Set" button
6. Send a new message and confirm that the reply reflects the character settings

[![Character Settings (System Prompt)](http://img.youtube.com/vi/YFY-Ne_u_jg/0.jpg)](https://youtu.be/YFY-Ne_u_jg)

## 4. File Processing Functions

### 4.1 File Summarization (Word, PPT, Excel, CSV)

1. Mention Party on Slack in a channel
2. Attach a file (Word, PPT, Excel, CSV)
3. Send the message
4. Confirm that "Summarize" and "Ask Questions" buttons are displayed
5. Click the "Summarize" button
6. Confirm that the file summary is posted to the thread

[![File Summarization (Word, PPT, Excel, CSV)](http://img.youtube.com/vi/MF5tZ4dq3SQ/0.jpg)](https://youtu.be/MF5tZ4dq3SQ)

### 4.2 URL Summarization

1. Mention Party on Slack in a channel
2. Send a message containing a URL
3. Confirm that "Ignore URL", "Summarize", and "Ask Questions" buttons are displayed
4. Click the "Summarize" button
5. Confirm that a summary of the URL content is posted to the thread

[![URL Summarization](http://img.youtube.com/vi/uKNJtmmFlmI/0.jpg)](https://youtu.be/uKNJtmmFlmI)

### 4.3 Image Recognition (Multimodal)

1. Mention Party on Slack
2. Select a model with a 📷 icon
3. Attach an image file
4. Describe in text what you want processed (e.g., "Explain the content of this image")
5. Send the message
6. Confirm that the AI recognizes the image and provides an appropriate response

[![Image Recognition (Multimodal)](http://img.youtube.com/vi/YN8XrjpyJdc/0.jpg)](https://youtu.be/YN8XrjpyJdc)

### 4.4 Audio File Transcription

1. Mention Party on Slack in a channel
2. Attach an audio file
3. Send the message
4. Confirm that "Transcribe", "Transcribe and Summarize", and "Transcribe and Ask Questions" buttons are displayed
5. Click the "Transcribe" button
6. Confirm that the audio transcription result is posted to the thread

[![Audio File Transcription](http://img.youtube.com/vi/Cth7xbC0EmE/0.jpg)](https://youtu.be/Cth7xbC0EmE)

## 5. Content Generation Functions

### 5.1 Image Generation

1. Mention Party on Slack
2. Click the image generation button in the thread menu
3. Enter a prompt for image generation
4. Send the message
5. Confirm that the generated image file is posted to the thread

[![Image Generation](http://img.youtube.com/vi/hSvpX7DeF2A/0.jpg)](https://youtu.be/hSvpX7DeF2A)

### 5.2 Voice Generation

1. Mention Party on Slack
2. Click the voice generation button in the thread menu
3. Enter the text you want to convert to speech
4. Send the message
5. Confirm that the generated audio file is posted to the thread

[![Voice Generation](http://img.youtube.com/vi/E7OHdksLfe4/0.jpg)](https://youtu.be/E7OHdksLfe4)

### 5.3 Canvas Creation Function

1. Mention Party on Slack
2. After some conversation with the AI, confirm that a Canvas creation button appears in the thread
3. Click the Canvas creation button
4. After waiting a while, confirm that the URL of the created Canvas is displayed

This feature is only available for Slack workspaces that support Canvas creation.

[![Canvas Creation Function](http://img.youtube.com/vi/1lA0eFVJmhs/0.jpg)](https://youtu.be/1lA0eFVJmhs)

## 6. Search and Integration Functions

### 6.1 Web Search Function

1. Mention Party on Slack
2. Set the Web Search button in the thread menu to "Use"
3. Select a model with a magnifying glass icon
4. Ask a question that requires current information
5. Confirm that the AI responds with web search results included

[![Web Search Function](http://img.youtube.com/vi/hdtz1iTUUss/0.jpg)](https://youtu.be/hdtz1iTUUss)

### 6.2 Ask Slack Function (Internal Search)

1. Mention Party on Slack
2. Click the "Ask Slack" button in the thread menu
3. Ask a question about messages within the workspace
4. Confirm that the AI searches Slack messages and responds

[![Ask Slack Function (Internal Search)](http://img.youtube.com/vi/nhVCi2Q8emg/0.jpg)](https://youtu.be/nhVCi2Q8emg)

### 6.3 Ask Slack Function (Summary Feature)

1. Mention Party on Slack
2. Click the "Ask Slack" button in the thread menu
3. Check the summary button
4. Select the channels, people, and time period you want to summarize
5. Send the message
6. Confirm that the summary result is posted to the thread

[![Ask Slack Function (Summary Feature)](http://img.youtube.com/vi/c8jFe3P9T9M/0.jpg)](https://youtu.be/c8jFe3P9T9M)

### 6.4 Pinecone Integration (Vector DB)

1. Set up the Pinecone API key in the app home screen
2. Set "Use Pinecone" button to "Use"
3. Add a 🍍 stamp to posts in channels
4. Confirm that the post is stored in Pinecone
5. When asking questions about that content, confirm that it references the stored information in responses

[![Pinecone Integration (Vector DB)](http://img.youtube.com/vi/ggrNAy-g3W0/0.jpg)](https://youtu.be/ggrNAy-g3W0)

### 6.5 Google Spreadsheet RAG

1. Allow Google integration in the app home screen
2. Register a Google Spreadsheet in the app home screen
3. Mention Party on Slack
4. Click the channel settings button in the thread menu
5. Set "Search Spreadsheet" to "Use"
6. Ask questions about the spreadsheet content and confirm appropriate responses

This feature uses OpenAI for RAG functionality.
Therefore, OpenAI API key registration is required.

[![Google Spreadsheet RAG](http://img.youtube.com/vi/CKuYpHJnAfw/0.jpg)](https://youtu.be/CKuYpHJnAfw)

## 7. Translation Functions

[![Translation Functions](http://img.youtube.com/vi/QfKWcMJSD10/0.jpg)](https://youtu.be/QfKWcMJSD10)

### 7.1 Stamp Translation Settings

1. Open the home screen
2. Click the "▶️ Use Stamp to Translation" button in the translation function section
3. Confirm that "🟢 When you add a country flag stamp or 🖋️, the post content will be translated" is displayed

Either DeepL API key, Google Cloud Service Account API Key, or LLM Model API key registration is required.

### 7.2 Translation Model Selection

1. Open the translation function section in the home screen
2. Select a translation model from the "Translation Model to Use" dropdown (LLM Model, DeepL, Google Translate)
3. Save the settings

Registered translation models can be used.
If the translation model is an LLM model, you can select the model for translation.

### 7.3 Translation Destination Settings (Thread/Channel)

1. Open the translation function section in the home screen
2. Select from the following options for translation content posting destination:
   - Thread only
   - Thread and channel
   - Channel only
3. Add country flag stamps (🇯🇵, 🇺🇸, etc.) to posts in channels
4. Confirm that translations appear in the selected posting destination

## 8. Automation and Scheduled Execution Functions

### 8.1 RSS Concierge

1. Mention Party on Slack
2. Click the RSS Concierge button in the thread menu
3. Click the register button
4. Enter the RSS feed URL and configure various settings
5. Click the register button
6. Confirm that new articles are posted to the channel once every hour

[![RSS Concierge](http://img.youtube.com/vi/V1FJtv9viME/0.jpg)](https://youtu.be/V1FJtv9viME)

### 8.2 LLM Log Transfer

1. Open the home screen
2. Click the "Open" button in the "LLM Log Transfer" section
3. Select the channel to transfer logs to
4. Save the settings
5. Confirm that input and output from app interactions are transferred to the log channel

[![LLM Log Transfer](http://img.youtube.com/vi/EboY8S8cfd4/0.jpg)](https://youtu.be/EboY8S8cfd4)

## 9. External Service Integration

### 9.1 Google Integration (Calendar Coordination)

1. Allow Google integration in the app home screen
2. Mention Party on Slack
3. Select the Google Calendar button in the thread menu
4. Select participants for schedule coordination
5. Select the dates and times to coordinate
6. Send the message
7. Confirm that schedule coordination results are posted to the thread
8. Select dates and times from the candidates
9. Perform the fix
10. Confirm that the event is created in Google Calendar

[![Google Integration (Calendar Coordination)](http://img.youtube.com/vi/X6nRFXyh7Lg/0.jpg)](https://youtu.be/X6nRFXyh7Lg)
