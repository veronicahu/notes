# github_ssh配置

1. 打开终端
2. 检查本地配置`ls -al ~/.ssh`
3. 输入`ssh-keygen -t ed25519 -C "your_email@example.com"`生成秘钥对，一路回车就可以。
4. 复制~/.ssh/id_ed25519.pub的内容`cat id_ed25519.pub`。
5. 在github-setting-SSH and GPG keys-New SSH key中，取个名字，输入刚才复制的内容。
6. 验证`ssh -T git@github.com`
7. 将项目的远程仓库地址更换为SSH的
8. 可以pull push了。