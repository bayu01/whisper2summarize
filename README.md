# Whisper2Summarize
[\[Google Colab\]](https://colab.research.google.com/github/AndreDalwin/Whisper2Summarize/blob/main/Whisper2Summarize_Colab_Edition.ipynb) 
![Cover Photo](/misc/cover.png)
Whisper2Summarize is an application that uses [Whisper](https://github.com/openai/whisper) for audio processing and [GPT](https://platform.openai.com/docs/api-reference) for summarization. It generates summaries of audio transcripts accurately, making it ideal for a variety of use cases such as note-taking, research, and content creation.

## Steps

1. `export OPENAI_KEY=xxxxxx`

2. `python whisper2summarize.py audio-file.m4a --model medium`

If Open AI APIs error out but already have the Transcript then run to skip translation:

`python whisper2summarize.py audio-file.m4a --model medium --file Transcript.txt`