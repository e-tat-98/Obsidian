https://cli.github.com/
# 🤔 What is GitHub CLI
GitHub CLI (`gh`) は、**GitHubのすべての操作をターミナル（コマンドライン）から実行できるようにする公式ツール**

通常、GitHub上で行う操作（プルリクエストの作成、Issueの管理、リポジトリのクローンなど）を、ブラウザを開かずにターミナルから完結させることができます。

# 🚀 Get start
Homebrewからインストール
``` zsh
╰─ brew install gh
```

GitHubのアカウントでログイン
``` zsh
╰─ gh auth login
? Where do you use GitHub? GitHub.com
? What is your preferred protocol for Git operations on this host? SSH 
? Upload your SSH public key to your GitHub account? /Users/user/.ssh/private_github.pub
? Title for your SSH key: GitHub CLI
? How would you like to authenticate GitHub CLI? Login with a web browser


! First copy your one-time code: B865-1DCF
Press Enter to open https://github.com/login/device in your browser...
✓ Authentication complete.
- gh config set -h github.com git_protocol ssh
✓ Configured git protocol
✓ SSH key already existed on your GitHub account: /Users/user/.ssh/private_github.pub
✓ Logged in as e-tat-98
```

# 📝 How to Use

see: https://cli.github.com/manual/