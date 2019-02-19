### Purpose

Run with ansible to provision all kinds of thing to you mac. This runs locally.

```
ansible-playbook local.yml --ask-sudo-pass
```

### TODO

* turn off dashboard for OSX: `defaults write com.apple.dashboard mcx-disabled -boolean YES && killall Dock`
