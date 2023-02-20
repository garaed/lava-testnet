tmux new -s lava-testnet-v060 "bash <(curl -s https://raw.githubusercontent.com/garaed/lava-testnet/main/auto_update.sh) -n lava -i lava-testnet-1 -t 82570 -v v0.6.0 -b lavad -c https://nodejumper.io/lava/cheat-sheet"

# CTRL+B D to exit the session
