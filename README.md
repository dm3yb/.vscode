# VSCode Customizations

---

#### How to Change VSCode Sidebar Styles

1. **Install the Extension:**
   - Install the [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) extension from the VSCode marketplace.

2. **Create a CSS File:**
   - Create a folder and a CSS file in your desired location. For example, `file:///Users/MyUserName/someFolder/editor.css`.

3. **Open User Settings:**
   - Press `Cmd + P`, type and select `>Preferences: Open User Settings (JSON)` to open the `settings.json` file.

4. **Add Custom CSS Path:**
   - Add the following property to your `settings.json` file:
     ```json
     "vscode_custom_css.imports": ["file:///Users/MyUserName/someFolder/editor.css"]
     ```

5. **Enable Custom CSS:**
   - Restart Visual Studio Code by pressing `Cmd + P`, typing and selecting `>Enable Custom CSS and JS`.

6. **Restart VSCode:**
   - In the lower right corner, click on `Restart Visual Studio Code`.

By following these steps, you can customize the sidebar styles in VSCode to your liking.

---