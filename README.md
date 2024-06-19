# Server-Setup-Scripts

To download, run the following command:

```bash
curl -O "https://raw.githubusercontent.com/Kayetic/Server-Setup-Scripts/main/general.sh" && chmod +x general.sh && sudo bash general.sh && rm general.sh
```

(This will download the script, make it executable, run it, and then delete it when it finishes.)

For a personal setup script, first download and setup zsh this:

```bash
sudo apt update
sudo apt upgrade -y
sudo apt install zsh
chsh -s $(which zsh)
```

Then restart the terminal (or close SSH connection to start a new one)
Choose option 0 to create a new .zshrc file

Then run the script below after downloading it with the command:

```bash
curl -O "https://raw.githubusercontent.com/Kayetic/Server-Setup-Scripts/main/setup.sh
```