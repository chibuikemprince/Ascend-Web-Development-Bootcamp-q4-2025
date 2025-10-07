# 📘 Ascend Web Development Bootcamp – Day 7

Today, we’re diving into **HTML Forms & User Input** — the foundation of interactive websites.
Forms are how users **send information** — from signing up on Jumia or Facebook, to logging into your bank’s online portal.

This guide explains the full code, what each tag does, and how it all works together.

---

# 👉 Watch the step-by-step video guide here:

🎥 [Bootcamp Live Class – Day 7](https://youtube.com/live/TxS4ALdqLO4?feature=share)

---

## 🛠️ Tools Required

You only need two things:

1. **A Code Editor**

   * Examples: [VS Code](https://code.visualstudio.com/), Sublime Text, or even Notepad.

2. **A Web Browser**

   * Chrome, Firefox, Edge, Safari, or any other.

---

## 📂 How to Create & Run the File

1. Open your **code editor**.
2. Create a new file named:

   ```bash
   index.html
   ```
3. Copy and paste the code below.
4. Save the file.
5. Open it in your browser by double-clicking it or using **Open With → Browser**.

---

## 💻 Full Code

```html
<!DOCTYPE html>
<html>
<head>
    <title> Registration Form </title>
</head>

<body> 
<h1> Registration Form </h1>

<form>
 <label> Full name </label> 
 <input type="text" placeholder="enter your name here" width="100px"/>
 <br/><br/>

 <label> Country </label> 
 <select>
    <option> Nigeria</option>
    <option> Ghana</option>
    <option> Togo</option>
    <option> Zambia</option>
 </select>
<br/><br/>

 <label> Gender - </label> 
 <br/><br/>
 Male <input type="radio" name="gender">
 Female <input type="radio" name="gender">
 <br/><br/>

 <label>Favourite Website </label>
 <br/>
 <input type="checkbox"> Softzenith<br/>
 <input type="checkbox"> Google<br/>
 <input type="checkbox"> YouTube<br/>
 <br/><br/>

 <label> Date of Birth </label>
 <input type="date"/>
 <br/><br/>

 <label>Password: </label> 
 <input type="password" required minlength="2" maxlength="5"/>
 <br/><br/>

 <label>Email</label> 
 <input type="email" required/>
 <br/><br/>

 <label>Profile Pic</label> 
 <input type="file"/>
 <br/><br/>

 <label> About Yourself </label>
 <textarea></textarea>
 <br/><br/>

 <input type="submit">
</form>

</body>
</html>
```

---

## 🧱 Line-by-Line Explanation

### 🏗 Document Setup

```html
<!DOCTYPE html>
<html>
<head>
    <title> Registration Form </title>
</head>
```

👉 Declares the document as HTML5 and sets the page title to “Registration Form”.

---

### 🧾 Page Header

```html
<h1> Registration Form </h1>
```

👉 The main heading of the page, displayed boldly at the top.

---

### 🧍 The `<form>` Tag

```html
<form>
```

👉 This tag creates a form — a container for collecting user inputs.
Everything inside it is part of the form.

---

### 🧑 Full Name Field

```html
<label> Full name </label> 
<input type="text" placeholder="enter your name here" width="100px"/>
```

👉 The `<label>` names the field, and `<input type="text">` allows users to type in their name.

* `placeholder` gives a hint to the user.
* Example: “Prince” or “Adaeze”.

---

### 🌍 Country Selector

```html
<label> Country </label> 
<select>
    <option> Nigeria</option>
    <option> Ghana</option>
    <option> Togo</option>
    <option> Zambia</option>
</select>
```

👉 The `<select>` tag creates a **dropdown list**, and each `<option>` is a selectable country.

💡 Example: Selecting “Nigeria” if you’re filling a form for NYSC registration.

---

### 🚹 Gender Options

```html
<label> Gender - </label>
Male <input type="radio" name="gender">
Female <input type="radio" name="gender">
```

👉 `<input type="radio">` allows users to pick **one option** out of many.

* The `name="gender"` ensures both buttons are linked, so only one can be selected at a time.

---

### 🌐 Favorite Website

```html
<label>Favourite Website </label>
<input type="checkbox"> Softzenith<br/>
<input type="checkbox"> Google<br/>
<input type="checkbox"> YouTube<br/>
```

👉 `<input type="checkbox">` allows **multiple selections**.
A user can choose all the websites they like.

---

### 🎂 Date of Birth

```html
<label> Date of Birth </label>
<input type="date"/>
```

👉 Lets users select a date from a mini calendar.

---

### 🔒 Password Field

```html
<label>Password: </label> 
<input type="password" required minlength="2" maxlength="5"/>
```

👉 Hides the characters typed by the user for security.

* `required` means the field must be filled before submitting.
* `minlength` and `maxlength` define password length limits.

---

### ✉️ Email Field

```html
<label>Email</label> 
<input type="email" required/>
```

👉 Ensures the user enters a **valid email format** (like `user@gmail.com`).

---

### 📁 Upload Profile Picture

```html
<label>Profile Pic</label> 
<input type="file"/>
```

👉 Allows users to upload a file (like a photo or document).

---

### 🧠 About Yourself

```html
<label> About Yourself </label>
<textarea></textarea>
```

👉 The `<textarea>` lets users write longer text, like a short bio or message.

---

### 🚀 Submit Button

```html
<input type="submit">
```

👉 Sends all the form data when clicked.

---

### 🧩 Closing Tags

```html
</form>
</body>
</html>
```

👉 Ends the form, body, and the full document.

---

## 🎯 Summary

✅ You learned how to:

* Build a **form** using `<form>`
* Collect user data with `<input>`, `<select>`, and `<textarea>`
* Use **checkboxes**, **radio buttons**, and **labels**
* Add **form validation** using `required`, `minlength`, and `maxlength`

---

## 💡 Real-Life Example

Think of filling a **job application** or **school registration form** online —
each question (name, gender, country, etc.) is powered by **HTML form elements** like the ones we built today.

---

## 🔗 Resources

📂 **GitHub Repository:**
[Ascend Web Development Bootcamp – Q4 2025](https://github.com/chibuikemprince/Ascend-Web-Development-Bootcamp-q4-2025/)

🎥 **Video Guide:**
[Watch Day 7 Live Session Replay](https://youtube.com/live/TxS4ALdqLO4?feature=share)
 