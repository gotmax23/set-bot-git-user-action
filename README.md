# set-bot-git-user-action

Set the Git config `user.name` and `user.email` based on a Github bot user so that the
commit authorship shows up properly on the web interface.
Defaults to setting the bot user to `github-actions`.


``` yaml
- name: Set Git user globally to github-actions
  uses: gotmax23/set-bot-git-user-action@main
  with:
    global: true
    bot: github-actions
    name: "Github Actions"
```
