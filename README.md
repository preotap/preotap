curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
source /root/.bashrc
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/refs/heads/main/llama-3.2-3b-instruct/config.json
gaianet start
gaianet info
