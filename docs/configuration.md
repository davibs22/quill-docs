---
sidebar_position: 2
---

# Configuration

## Generating the configuration file
To generate the configuration file, run the following command:
```bash
quill config
```
## Configuration file
The configuration file is located at `~/.config/quill/config.yaml`.
```yaml
preferences:
    llama:
        apiurl: "http://localhost:11434/api/generate"
        model: "llama3.2:latest"
    openai:
        apikey: ""
        model: ""
    providerdefault: "llama"
```

## Configuration options
The configuration file contains the following options:
- `preferences`: This section contains the preferences for the different providers.
    - `llama`: This section contains the preferences for the llama provider.
        - `apiurl`: The URL of the llama API.
        - `model`: The model to use for the llama provider.
    - `openai`: This section contains the preferences for the openai provider.
        - `apikey`: The API key for the openai provider.
        - `model`: The model to use for the openai provider.
    - `providerdefault`: The default provider to use.