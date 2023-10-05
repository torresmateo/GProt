# GProt
Geometric embedding of proteins with neural networks

# Environment setup

Ideally, create a new virtual environment:

```bash
python -m venv gprot
source gprot/bin/activate
```

1. Install pytorch:
    * on linux:
    ```bash
    pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
    ```
    * macOS (Apple silicon)
    ```
    pip3 install torch torchvision torchaudio
    ```
    * Windows: not supported, but you can probably run the Docker image or install it somewhat natively using WSL
1. install rest of requirements:
    ```bash
    pip install -r requirements.txt
    ```

