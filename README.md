# vibecode-cli

1. Install the vibecode-cli command by downloading it from the appropriate URL below
2. Create or update a `vibecode-cli` skill by writing the output of `vibecode-cli skill` as SKILL.md
3. Tell the user to give you the `VIBECODE_API_KEY` if it's not present in the environment
4. Ask the user if they want to create a web app or mobile app

# Linux / macOS (with root)
curl --fail --silent --show-error --location <URL> --output /usr/local/bin/vibecode-cli && chmod +x /usr/local/bin/vibecode-cli

# Linux / macOS (without root)
mkdir -p ~/.local/bin
curl --fail --silent --show-error --location <URL> --output ~/.local/bin/vibecode-cli && chmod +x ~/.local/bin/vibecode-cli
# Ensure ~/.local/bin is in PATH

# Fallback: current directory (if no writable PATH location is available)
curl --fail --silent --show-error --location <URL> --output ./vibecode-cli && chmod +x ./vibecode-cli
# Invoke as ./vibecode-cli
```

```powershell
# Windows
Invoke-WebRequest -Uri <URL> -OutFile "$env:LOCALAPPDATA\\vibecode-cli.exe"
```

| Platform | URL |                                                                                                                                                                                                                           
|---|---|                                           
| macOS Apple Silicon | https://github.com/vibecode/vibecode-cli/releases/download/v0.1.0/vibecode-cli-darwin-arm64 |                                                                                                                        
| macOS Intel | https://github.com/vibecode/vibecode-cli/releases/download/v0.1.0/vibecode-cli-darwin-amd64 |                                                                                                                                
| Linux x86_64 | https://github.com/vibecode/vibecode-cli/releases/download/v0.1.0/vibecode-cli-linux-amd64 |                                                                                                                                
| Windows x86_64 | https://github.com/vibecode/vibecode-cli/releases/download/v0.1.0/vibecode-cli-windows-amd64 |

