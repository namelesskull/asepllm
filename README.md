## Installation

### Linux

**x86_64 (Intel/AMD):**
```bash
sudo curl -L https://github.com/namelesskull/asepllm/releases/download/v0.1.0/asepllm-x86_64 \
  -o /usr/local/bin/asepllm && sudo chmod +x /usr/local/bin/asepllm
```

**aarch64 (ARM):**
```bash
sudo curl -L https://github.com/namelesskull/asepllm/releases/download/v0.1.0/asepllm-aarch64 \
  -o /usr/local/bin/asepllm && sudo chmod +x /usr/local/bin/asepllm
```

### macOS

**Apple Silicon (M1/M2/M3):**
```bash
sudo curl -L https://github.com/namelesskull/asepllm/releases/download/v0.1.0/asepllm-aarch64 \
  -o /usr/local/bin/asepllm && sudo chmod +x /usr/local/bin/asepllm
```

**Intel Mac:**
```bash
sudo curl -L https://github.com/namelesskull/asepllm/releases/download/v0.1.0/asepllm-x86_64 \
  -o /usr/local/bin/asepllm && sudo chmod +x /usr/local/bin/asepllm
```

> **macOS only:** If you see _"cannot be opened because the developer cannot be verified"_, run:
> ```bash
> sudo xattr -d com.apple.quarantine /usr/local/bin/asepllm
> ```

### Verify Installation

```bash
asepllm
```
