# ⚡ GitHub Activity Booster

This is a automated GitHub Actions workflow designed to maintain a consistent contribution graph by making periodic commits to the repository.

## 🚀 How It Works
- **Schedule:** Runs every 2 hours.
- **Logic:** Uses a random number generator to decide whether to commit (90% success rate).
- **Update:** Appends a timestamp to `activity.txt` to trigger a commit.

## 🛠️ Installation & Setup

1. **Token Creation:** Generate a Personal Access Token (PAT) with `repo` and `workflow` permissions.
2. **Secrets:** Add the PAT to your repository secrets under the name `PAT`.
3. **Configuration:** Ensure the `random-commit.yml` is located in `.github/workflows/`.

## 📊 Status
The bot logs all successful operations in the `activity.txt` file for transparency.

---
*Maintained by Sayan (SONU)*
