 # 📘 Ascend Web Development Bootcamp – Day 6

This README will guide you through the HTML code for **Tables**.
You’ll learn how to organize information neatly using **rows**, **columns**, and **headers**, and how to use basic HTML attributes for styling.

---

# 👉 Watch the step-by-step video guide here:

🎥 [Day 6 Live Session Replay](https://www.youtube.com/watch?v=6c8BYY25zQY&t=76s)

---

## 🛠️ Tools Required

To run this code, you only need the following:

1. **A Code Editor**

   * Examples: [VS Code](https://code.visualstudio.com/), Sublime Text, Notepad++
   * You can even use **Notepad** (Windows) or **TextEdit** (Mac).

2. **A Web Browser**

   * Examples: Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, Opera, Brave

---

## 📂 How to Create & Run the File

1. Open your **code editor**.
2. Create a new file and name it:

   ```bash
   index.html
   ```
3. Copy and paste the code below into the file.
4. Save the file.
5. Open it in your **web browser** by:

   * Double-clicking the file, **or**
   * Right-click → **Open With** → select your browser.

---

## 💻 Code Explanation

Here’s the full code first:

```html
<!DOCTYPE html>
<html>

<head>
    <title>
        HTML TABLES
    </title>
</head>

<body>

    <table border="3" cellpadding="25" cellspacing="20" width="100px" bgcolor="white" align="center">
        <caption>RESULT SHEET</caption>

        <tr>
            <th>Name</th>
            <th>Class</th>
            <th>Score</th>
        </tr>

        <tr>
            <td>Prince</td>
            <td>A</td>
            <td>90</td>
        </tr>

        <tr>
            <td>Precious</td>
            <td>A</td>
            <td>88</td>
        </tr>

        <tr>
            <td>Samuel</td>
            <td>B</td>
            <td>85</td>
        </tr>

        <tr>
            <td>Joy</td>
            <td>C</td>
            <td>78</td>
        </tr>

        <tr>
            <td>Soteria</td>
            <td>B</td>
            <td>80</td>
        </tr>
    </table>

</body>

</html>
```

---

### 🧱 Line-by-Line Breakdown

```html
<!DOCTYPE html>
```

👉 Declares this as an **HTML5 document**.

```html
<html>
```

👉 The root element that contains everything in your webpage.

```html
<head>
```

👉 The `<head>` section stores information about your page, such as the title.

```html
<title>HTML TABLES</title>
```

👉 Sets the name that appears in your browser tab.

```html
</head>
```

👉 Closes the head section.

```html
<body>
```

👉 This is where the visible content goes — everything the user sees.

---

### 📊 Creating the Table

```html
<table border="3" cellpadding="25" cellspacing="20" width="100px" bgcolor="white" align="center">
```

👉 The `<table>` tag starts your table.

* `border="3"` → Adds a thick border around the table and cells.
* `cellpadding="25"` → Adds space inside each cell (like padding).
* `cellspacing="20"` → Adds space between the cells.
* `width="100px"` → Sets the width of the table.
* `bgcolor="white"` → Sets the background color.
* `align="center"` → Centers the table on the page.

---

### 🏷️ Table Caption

```html
<caption>RESULT SHEET</caption>
```

👉 The **caption** gives your table a title that appears above it.

---

### 📋 Table Headings

```html
<tr>
    <th>Name</th>
    <th>Class</th>
    <th>Score</th>
</tr>
```

👉 `<tr>` defines a **table row**, and `<th>` defines **table headers**.
Headers are usually bold and centered by default.

---

### 👥 Table Data Rows

```html
<tr>
    <td>Prince</td>
    <td>A</td>
    <td>90</td>
</tr>
```

👉 `<td>` defines **table data** — the actual content inside each cell.
Each `<tr>` creates a new row of data.

You can repeat this for each student record.

---

### 🔚 Closing Tags

```html
</table>
```

👉 Closes the table.

```html
</body>
</html>
```

👉 Closes the body and the entire HTML document.

---

## 🎯 Summary

✅ **What you learned:**

* How to create a table with `<table>`, `<tr>`, `<th>`, and `<td>`
* How to add a caption
* How to use HTML attributes (`border`, `cellpadding`, `cellspacing`, `align`, `bgcolor`)
* How to display structured data neatly

---

## 📘 Real-Life Example

Imagine you’re designing a **Result Sheet** for a school in Nigeria.
Each student’s name, class, and score can be displayed neatly using a table — it’s clear, organized, and easy to understand.

This same concept can be used for:

* Product price lists
* Attendance records
* Data comparison tables

---

## 🔗 Resources

📂 **GitHub Repository:**
[Ascend Web Development Bootcamp – Q4 2025](https://github.com/chibuikemprince/Ascend-Web-Development-Bootcamp-q4-2025/)

 
