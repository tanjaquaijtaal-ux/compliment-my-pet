# 🚀 Quick Start Guide

Get your Compliment My Pet agent up and running in minutes!

## For First-Time Setup (Adding Your Export)

### Step 1: Export Your Agent from Copilot Studio
1. Open [Microsoft Copilot Studio](https://copilotstudio.microsoft.com/)
2. Open your "Compliment My Pet" agent
3. Click **Settings** (gear icon) → **General**
4. Scroll down to **Export**
5. Click **Export agent**
6. Download the `.zip` file when ready

### Step 2: Add Files to Repository
1. Place the exported `.zip` file in the `export/` folder
2. Delete the `export/PLACEHOLDER.md` file
3. Take screenshots of your agent (see below)
4. Add screenshots to the `screenshots/` folder
5. Delete the `screenshots/PLACEHOLDER.md` file

### Step 3: Take Screenshots
You need 4 screenshots:

| Screenshot | What to Capture | File Name |
|------------|----------------|-----------|
| Banner | Agent logo or welcome screen | `banner.png` |
| Main Interface | Chat interface | `main-interface.png` |
| Example | Live conversation with compliment | `example-interaction.png` |
| Configuration | Copilot Studio overview | `agent-configuration.png` |

**How to take them:**
- Windows: `Win + Shift + S`
- Mac: `Cmd + Shift + 4`
- Save to `screenshots/` folder

### Step 4: Update Version Info (Optional)
Edit `export/README.md` and update the version history table.

### Step 5: Commit and Share
```bash
git add .
git commit -m "Add Copilot Studio export and screenshots"
git push
```

Done! Your agent is now documented and ready to share! 🎉

---

## For Users Importing the Agent

### Step 1: Download the Export
1. Go to the `export/` folder
2. Download the `.zip` file

### Step 2: Import to Copilot Studio
1. Open [Microsoft Copilot Studio](https://copilotstudio.microsoft.com/)
2. Click **Agents** → **Import**
3. Select the downloaded `.zip` file
4. Follow the import wizard
5. Click **Import**

### Step 3: Test the Agent
1. Open your imported agent
2. Click **Test your agent**
3. Upload a pet photo or describe your pet
4. Enjoy the compliments! 🐾

### Step 4: Deploy (Optional)
- **Microsoft Teams**: Publish to Teams channel
- **Website**: Embed in your website
- **Custom**: Use the agent API

---

## 🆘 Troubleshooting

**Import fails?**
- Check you have admin rights in Copilot Studio
- Verify the .zip file isn't corrupted
- Try re-downloading the export

**Agent doesn't respond?**
- Ensure it's published (not just saved)
- Check the Topics are enabled
- Review error logs in Copilot Studio

**Can't find export button?**
- You need appropriate Copilot Studio license
- Check Settings → General → Export section
- Contact your admin for permissions

---

## 📚 Need More Help?

- **Full README**: See [README.md](README.md) for complete documentation
- **Export Guide**: Check [export/README.md](export/README.md)
- **Screenshots Guide**: See [screenshots/README.md](screenshots/README.md)
- **Contributing**: Read [CONTRIBUTING.md](CONTRIBUTING.md)

---

**Questions?** Open an issue on GitHub or consult the [Copilot Studio docs](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)!

