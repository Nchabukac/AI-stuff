## Requirements
- Claude code
- Deepseek API key

## 1.Installing Claude Terminal
Type `curl -fsSL https://claude.ai/install.sh | bash`

<img width="1060" height="457" alt="image" src="https://github.com/user-attachments/assets/efcd2c94-ca40-44f6-9f1b-910943304553" />

NB: **If you are still required to login after installing claude via npm and after setting the environment variables, you'll have to add `export ANTHROPIC_API_KEY=<your DeepSeek API Key>`, 
launch claude, exit, then `unset ANTHROPIC_API_KEY=<your DeepSeek API Key>` and launch claude again.**

**Adding ~/.local/bin to your PATH.**

<img width="1457" height="124" alt="image" src="https://github.com/user-attachments/assets/29b92b40-f315-4ef2-bb2b-4528041e0c2a" />

**After installation, open a terminal in the project you want to work in and start Claude Code.**
`claude`

<img width="1291" height="667" alt="image" src="https://github.com/user-attachments/assets/6e07fad9-d728-46e6-84c2-9e5125b51cac" />

You will notice you need to login but because we want to use deepseek we'll setup several environment variables and use claude without logging in.

## 2.Deepseek API KEY
Create one at https://platform.deepseek.com/api_keys, you will need to top up some money to use the API.

**NB: You need to store it safely and immediately because you will see it once.**

<img width="973" height="354" alt="image" src="https://github.com/user-attachments/assets/c688c256-28fd-40af-ac73-4ead0a9b0e03" />

## 3.Setting up Environment variables
Commands below are from https://api-docs.deepseek.com/guides/coding_agents
```
export ANTHROPIC_BASE_URL=https://api.deepseek.com/anthropic
export ANTHROPIC_AUTH_TOKEN=<your DeepSeek API Key>
export ANTHROPIC_MODEL=deepseek-v4-pro[1m]
export ANTHROPIC_DEFAULT_OPUS_MODEL=deepseek-v4-pro[1m]
export ANTHROPIC_DEFAULT_SONNET_MODEL=deepseek-v4-pro[1m]
export ANTHROPIC_DEFAULT_HAIKU_MODEL=deepseek-v4-flash
export CLAUDE_CODE_SUBAGENT_MODEL=deepseek-v4-flash
export CLAUDE_CODE_EFFORT_LEVEL=max
```
After running the above, launch claude

<img width="1357" height="226" alt="Screenshot From 2026-05-07 09-31-17" src="https://github.com/user-attachments/assets/08a4d68e-d77e-40c3-bad3-64ad6ae2a68e" />

## 4.Creating a simple snake game
<img width="1235" height="484" alt="image" src="https://github.com/user-attachments/assets/3b07e7ce-0576-401c-b27c-343a5a8d6d8e" />

<img width="813" height="674" alt="image" src="https://github.com/user-attachments/assets/e2d5589f-e0af-4d60-aba3-42ebc57f3b35" />

## 5.Monitoring token usage
https://platform.deepseek.com/usage
<img width="988" height="801" alt="image" src="https://github.com/user-attachments/assets/16c0871d-7832-4e37-8d2c-1ef8b5234e8e" />

