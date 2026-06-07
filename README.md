# lc - Personal Terminal Session Recorder

A lightweight tool for Ubuntu/Linux to record your active terminal session and save critical project commands to a local text log before they vanish.

## 🚀 One-Line Installation

Run this single command in your terminal to instantly install `lc`:

```bash
curl -sSL https://githubusercontent.com -o ~/bin/lc && chmod +x ~/bin/lc && source ~/.profile
```

*(Note: Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username).*

## 📖 How to Use
1. Type `lc` to start your active tracking workspace. Your prompt will change to `(lc)`.
2. Run your development or system tasks normally.
3. Type `lc add` immediately after a critical command to save it permanently.
4. Type `lc list` anywhere to inspect your last 10 saved lines instantly.
5. Type `exit` to close the session safely.

### 🔋 Battery Protection (Auto-Save)
While inside the `lc` workspace, an automated background helper copies your live shell activity to `~/project_logs/autosave_backup.log` every 5 minutes. If your laptop loses power unexpectedly, your recent workspace memory is safe.

## 🗑️ Uninstallation

If you ever want to cleanly remove `lc` and all its files from your system, run this command:

```bash
rm -f ~/bin/lc && rm -rf ~/project_logs && echo "lc has been fully removed."
```

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
