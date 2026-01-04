# Megabonk Local Save Files

## 🧰 Backup Recommendation

Before making any changes, copy the original files and store them somewhere safe


## 📁 Files Included

- **progression.json**  
  Stores progression-related data

- **stats.json**  
  Stores player statistics and tracked values

---

## ⚠️ Important Notes

- Always **close the game before modifying save files**.
- **Make a backup** of your original files before overwriting anything.
- Use this repository **at your own risk**.

---

## 📌 How to Apply the Save Files

### Method 1 — Copy & Paste Content

1. Close **Megabonk**
2. Press `Win + R` and type: `%appdata%`
3. Navigate **one directory back** to: `..\LocalLow\Ved\Megabonk\Saves\CloudDir\<id>\`
4. Open `progression.json` and/or `stats.json`
5. **Replace the entire content** with the content from this repository
6. Save the files
7. Launch the game

### Method 2 — Replace Files Directly

1. Close **Megabonk**
2. Press `Win + R` and type: `%appdata%`
3. Navigate **one directory back** to: `..\LocalLow\Ved\Megabonk\Saves\CloudDir\<id>\`
4. Download the files from this repository
5. **Overwrite** the existing files:
- `progression.json`
- `stats.json`
6. Launch the game

---

## ☁️ Steam Cloud Conflict

If Steam shows a **Cloud Sync Conflict** message:

- Choose **Use Local Save**
- Steam will automatically sync the local files to the cloud

This is expected behavior.

---

# 💻Megabonk Save Editor

## ⚠️How to Use

### 1. Open the Editor
- Open the `save_editor.html` file in your browser (Chrome, Firefox, Edge).

### 2. Select the Save File
- Click **Select file…**
- Choose one of the Megabonk save files (for example `progression.json` or `stats.json`).

### 3. Load the File
- Click **Load**  
- The file contents will appear in the editor.

### 4. Decrypt
- Click **Decrypt**  
- The encrypted content will be converted into readable text.
- If the file is valid, the status indicator will turn green.

### 5. Edit
- Modify the decrypted content directly in the editor.
- If the content is valid JSON, the editor will indicate it automatically.

### 6. Encrypt
- After finishing your edits, click **Encrypt**  
- The content will be converted back to the encrypted format expected by the game.

### 7. Save
- Click **Save**
- The edited file will be downloaded with the same filename.

### 8. Replace the Save File
- Copy the saved file to:`<drive>:\Users\<user>\AppData\LocalLow\Ved\Megabonk\Saves\CloudDir\<id>\`

### 📝Notes
- ✅Green indicator = valid state  
- 🔴Red indicator  = invalid or failed operation  
- 🔶Yellow/neutral indicator = not yet checked

