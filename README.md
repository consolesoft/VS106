---

# 📦 V&S106

This tool helps you **automatically validate and sort and organize a list of email addresses** into different folders based on their email providers (like Gmail, Yahoo, Outlook, etc.).

It’s great for anyone who works with lots of emails and wants to group them quickly by the service they use the valid or invalid or deliverable one.

---

## ✨ Features

* ✅ Automatically detects email providers (Gmail, Outlook, Yahoo, etc.)
* 📁 Creates folders and pre-named text files for 100+ common email providers
* 📂 Saves valid and invalid emails separately
* 📡 Checks if an email is real
* 📥 Lets you choose a file using a pop-up dialog
* 🧠 use high arch to validate and sort email at one

---

## 📦 What You Need

* This program runs on your **desktop** (Windows, macOS, or Linux)
* You need a **.txt file** that contains your list of email addresses (just plain text, one line or mixed text)

---

## 🚀 How To Use It

1. **Run the program** – It will open a window asking you to select a `.txt` file from your computer.
2. **Select your file** – Pick the file that contains emails.
3. The tool will:

   * Scan the file
   * Detect the email addresses
   * Validate Email if good or bad if deleverable or not
   * Figure out which provider (like Gmail or Yahoo) each email belongs to
   * Automatically save those emails into separate files like `gmail.txt`, `yahoo.txt`, `outlook.txt`, etc.
   * Put everything into a folder named `results/your-project-name`
4. Done! 🎉 You’ll find your sorted emails nicely saved in one place.

---

## 📝 Output Example

Let’s say your file had:

```
john@gmail.com,
mary@yahoo.com,
steve@outlook.com.
```

You’ll find:

```
results/
└── your-project-name/
    ├── gmail.txt         → john@gmail.com
    ├── yahoo.txt         → mary@yahoo.com
    ├── outlook.txt       → steve@outlook.com
    ├── valid.txt         → all valid emails
    ├── invalid.txt       → any that don’t look like real emails
```

---

## 🛠 Behind The Scenes (Just FYI)

The tool:

* Reads your text file
* Uses smart patterns to find emails
* Contacts online services (optional) to validate
* Checks if the email domain has real mail servers
* Sorts them into appropriate files for you

---

## 💬 Support

If you have any issues using the tool, reach out to us at \[[support@yourdomain.com](mailto:support@yourdomain.com)] or [GitHub Issues](https://github.com/concolesoft/purple/issues).

---

## 🧾 License

This tool is provided "as is" for personal or business use.

---

