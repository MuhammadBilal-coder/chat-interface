# GitHub Desktop — upload guide

1. Download and extract `Relay-Chat-App.zip`. Open the extracted `chat-interface` folder and confirm `index.html`, `style.css`, `script.js` and `README.md` are directly inside it.
2. In GitHub Desktop, select **File > Add Local Repository > Choose**. Select the `chat-interface` folder (not the outer ZIP/extraction folder).
3. When it says the directory is not a Git repository, click the blue **create a repository** link. Set Name to `chat-interface`, Description to `Responsive frontend-only chat with instant messages, timestamps, predefined chatbot replies and persistent history.`, Git ignore to None, License to None, and leave Initialize with a README unchecked. The README and ignore file already exist. Confirm the local path points to the existing project folder. Click **Create Repository**.
4. Check the **History** tab for Initial commit. If the Changes tab has uncommitted files, type `Add complete chat-interface project` in Summary and click **Commit to main**. Ensure all source files were committed.
5. Click **Publish repository**. Use Name `chat-interface`. Leave Organization at your personal account unless required otherwise. Uncheck **Keep this code private** if the evaluator needs public access. Click **Publish Repository** again.
6. Open the repository using **Repository > View on GitHub** (or Ctrl+Shift+G on Windows). Confirm the code, README and screenshot are visible, and copy the actual address from the browser. Example format: `https://github.com/YOUR-USERNAME/chat-interface`.
7. Submit the repository URL in the appropriate internship task. Do not submit the ZIP or a different repository unless specifically requested.

## Optional live demo

If a live URL is requested: on the GitHub repository page go to Settings > Pages > Deploy from a branch > main > / (root) > Save. Wait for GitHub's deployment to succeed and copy the published URL displayed in Pages. Example: `https://YOUR-USERNAME.github.io/chat-interface/`. GitHub Pages is not required by the supplied task instructions alone; follow any separate internship submission rules.

## Quick checks

- Separate repository for this task.
- Correct folder (index.html in repository root).
- All files committed and published.
- Public access or evaluator access granted.
- Correct repository URL submitted.
