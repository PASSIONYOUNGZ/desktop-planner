# Desktop Planner user guide

[Project home](../README.en.md) · [简体中文](usage.zh-CN.md)

## Get started

1. [Download](../README.en.md#download) the Local or Full Windows x64 ZIP. Full adds optional Feishu sync.
2. Extract the whole ZIP to a folder you can write to and run `DesktopPlanner.exe`. Keep the DLLs and configuration file beside it.
3. Click **Add** or press `Ctrl+N` to create a task. Click the circle to complete it, the pencil to edit it, or the trash icon to delete it.

The app uses .NET Framework 4.8 or 4.8.1 and supports Windows 10 version 1903 or later and Windows 11. Change the language or the new-task shortcut under **Settings → General**.

## Plan and dock

- Use the arrows to switch days or click the date to open the calendar. Choose **Week plan** to work on a Monday-to-Sunday plan.
- Drag tasks to reorder them. For daily tasks, drag the card past either side of the task list to change dates, then move it back into the list and drop it in place. Press `Esc` to cancel.
- When today's list is empty, you can carry over unfinished tasks from yesterday. The original tasks remain in yesterday's history.
- Drag the title bar to move the window. When unpinned, it tucks into the nearest edge after the pointer leaves. Hover over the edge tab to reopen it. The pin keeps the panel open, and the close button hides it to the system tray. Use the tray menu to quit.

## Review, export, and back up

- Open the overview to check the last seven days, a calendar week, a calendar month, or all time. Scroll through dated tasks or open the complete history.
- In **Settings → Data**, export all records, this week, or this month as Markdown or Word. The export uses the records available locally in your current workspace.
- Plans and quote history are stored in `Data\planner.json`. The Feishu cache and pending changes are stored in `Data\sync.json`. Exit the app before moving, backing up, or copying its `Data` folder to another edition.
- Preferences and Feishu authorization are stored in `%LOCALAPPDATA%\DesktopPlanner`. They follow your Windows user account on that PC. Check for updates under **Settings → General → About & updates**.

## Sync with Feishu

1. In the Full edition, open **Settings → Data** and paste a Feishu document or wiki link you can edit. An empty document dedicated to your plans works well.
2. Click **Connect Feishu**. The app tries saved authorization first and opens your browser when authorization is needed. Check the document's sharing settings if your account cannot edit it.
3. Edit tasks from the app or the document. Desktop Planner groups the document by calendar week and uses `YYYY-MM-DD` date headings followed by numbered task paragraphs.

Local and Feishu workspaces save their plans separately. You can share plans across Windows PCs by connecting to the same Feishu document and authorizing each PC. You can also open the document in Feishu on your phone.

When you switch documents, Desktop Planner checks access with your existing authorization first. If Feishu revokes the refresh credential or it expires, reauthorize from the Data settings. [Official Feishu CLI](https://github.com/larksuite/cli)
