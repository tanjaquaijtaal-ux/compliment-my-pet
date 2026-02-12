# Export Files

This folder contains the Copilot Studio export file(s) for the Compliment My Pet agent.

## 📦 What to Place Here

Place your Copilot Studio export `.zip` file in this directory. The export should include:

- Agent configuration
- Topics and conversation flows
- Entities (if any)
- Variables and settings
- Any custom actions or skills

## 📤 How to Export from Copilot Studio

If you need to create or update the export file:

1. Open your agent in [Microsoft Copilot Studio](https://copilotstudio.microsoft.com/)
2. Navigate to **Settings** > **General**
3. Scroll to the **Export** section
4. Click **Export agent**
5. Wait for the export to complete
6. Download the `.zip` file
7. Place it in this `export` folder
8. Commit and push to the repository

## 📋 Naming Convention

Recommended naming format: `compliment-my-pet-agent-v[version].zip`

Examples:
- `compliment-my-pet-agent-v1.0.zip`
- `compliment-my-pet-agent-v1.1.zip`
- `compliment-my-pet-agent-2024-02-12.zip`

## ⚠️ Important Notes

- The export file may contain sensitive configuration data
- Review the export before committing to ensure no secrets or API keys are included
- Keep the export file updated when you make significant changes to the agent
- Document any version changes in the main README.md changelog

## 🔄 Version History

| Version | Date | Description |
|---------|------|-------------|
| v1.0    | TBD  | Initial release |

