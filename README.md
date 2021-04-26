# Text to commands shell tool

Text to commands shell tool, uses GPT3

## Why?

Tired of forgetting how to do things in the terminal? Like killing processors listening to some port? Creating certificates with OpenSSL? Maybe even check the weather? Always having to search on Google how to do it and which link in Google you should check and blah blah blah ... so I've created a shell tool that lets you do everything you could do in the terminal normally but also lets you request commands in free text and get back the relevant command. Example in the video :)

Inspired by "River's Educational Channel"

## App usage

```bash
git clone https://github.com/GabiCtrlZ/open-ai-shell.git
pip install -r requirements.txt
```

envs
```bash
OPENAI_API_KEY={{your open ai api key goes here}}
```

run 
```bash
python shell.py
```

and you can you the shell just like any other shell with the added feature of querying GPT3 every time you start a line with "->"

## pictures

Example:

<img src="https://raw.githubusercontent.com/GabiCtrlZ/open-ai-shell/main/example.png" alt="example"  />
