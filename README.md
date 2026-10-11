# 🐧 linux-recovery

> My personal notes for getting my Linux skills back on track.

A cheat sheet of the Linux commands I use every day, with short explanations and practical examples. I'm learning with the help of ChatGPT and [Jadi](https://jadi.net)'s Linux course.

## 📂 What's inside

| File | Description |
|------|-------------|
| [`text.txt`](text.txt) | The main cheat sheet: commands, short explanations and examples, grouped into 25 sections |

## 📚 Topics covered

1. Recommended terminal setup
2. Navigation
3. Files and directories
4. Viewing and editing files
5. Searching (`find`, `grep`, `which`)
6. Text processing (`wc`, `sort`, `uniq`, `cut`, `sed`, `awk`)
7. Redirection and pipes
8. Help and shell tricks
9. System information
10. Disk and storage
11. Processes and jobs
12. Users and groups
13. Permissions and ownership
14. Archives and compression
15. Network
16. SSH and file transfer
17. Links
18. Package management (`apt`)
19. Services and logs (`systemctl`, `journalctl`)
20. Scheduled tasks (`cron`)
21. Monitoring memory (RAM)
22. Monitoring CPU
23. Power
24. Keyboard shortcuts
25. Quick danger list

## 🛠️ Recommended terminal setup

| Tool | What it does |
|------|--------------|
| [oh-my-zsh](https://ohmyz.sh) | Framework for managing zsh |
| [Powerlevel10k](https://github.com/romkatv/powerlevel10k) | Fast and pretty zsh theme |
| [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) | Suggests commands as you type |
| [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) | Colors valid and invalid commands |
| [eza](https://github.com/eza-community/eza) | Modern replacement for `ls` |
| [bat](https://github.com/sharkdp/bat) | Modern replacement for `cat` |
| [btop](https://github.com/aristocratos/btop) | Resource monitor |
| [tmux](https://github.com/tmux/tmux) | Multiple terminal sessions in one window |
| [fastfetch](https://github.com/fastfetch-cli/fastfetch) | System info with a logo |

## 🚀 How to use

```bash
git clone https://github.com/mohamad-saleh-git/linux-recovery.git
cd linux-recovery
less text.txt
```

Tip: search for a command quickly with `grep`:

```bash
grep -n "chmod" text.txt
```

## ⚠️ Warning

These notes are for personal use. Some commands are destructive, so double-check before running them:

- `rm -rf`: deletes without asking and without undo
- `shred`: destroys data permanently
- `dd`: a wrong target can wipe a disk
- `chmod -R 777`: gives everyone full access

## 🙏 Credits

- [Jadi](https://jadi.net) for the Linux course
- ChatGPT and Claude for help with learning and writing these notes
