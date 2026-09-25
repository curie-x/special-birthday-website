# 🎂 Special Birthday Website 💖

### Make someone's birthday a little more special. ✨

A cute, interactive and fully customizable birthday website made for creating a **personal digital birthday surprise** for someone special.

It includes animated birthday content, background music, interactive flower & emoji effects, a photo scrapbook, sticky notes, an animated envelope letter and more. 🌸🎁

> 💡 **The idea is simple:**
> Change the name, replace the photos, choose a birthday song, customize the messages — and you're ready to surprise someone. ❤️

---

## ✨ Features

🎂 **Animated Birthday Experience**
A full-screen animated birthday greeting with decorations and effects.

🎵 **Background Birthday Music**
Play your favorite birthday song with built-in play, pause, mute and volume controls.

🌸 **Click Effects**
Click anywhere on the website and flowers, hearts, stars and other emojis appear with animations.

🎉 **Celebration Effects**
Buttons trigger a burst of flowers, cakes, hearts, stars and other celebration emojis.

📸 **Memory Scrapbook**
A cute scrapbook-style section for displaying personal photos.

📝 **Sticky Notes**
Add your own wishes, memories, funny messages or personal notes.

💌 **Animated Letter**
An interactive envelope opens to reveal a personal birthday message.

💖 **Personalized Content**
Change the name, photos, music, birthday date and messages to make the website unique.

📱 **Responsive Design**
Designed to work on both desktop and mobile devices.

---

# 🎨 Make It Personal

You don't need to rebuild the website.

Just customize a few things and you're ready to go.

## 👤 1. Change the Name

The current version is made for **Maria**.

Search the project for:

```text
Maria
```

and replace it with your special person's name.

There are several places where the name appears, including the page title, greeting, photo section and birthday letter.

For example:

```html
<title>Happy Birthday Maria</title>
```

becomes:

```html
<title>Happy Birthday HER NAME</title>
```

And:

```html
<span>Dear Maria</span>
```

becomes:

```html
<span>Dear HER NAME</span>
```

---

## 📸 2. Replace the Photos

The scrapbook currently uses multiple photos.

Replace the existing images with your own photos and update their filenames if needed.

The main birthday photo is:

```text
images/k10.png
```

The scrapbook photos are:

```text
images/k13.jpg
images/k11.jpg
images/k12.jpg
```

So you can simply replace these images with photos of your special person while keeping the same filenames.

Or change the paths in the HTML if you prefer different filenames.

---

## 🎵 3. Change the Birthday Song

The current website uses:

```text
audio/Maria.mp3
```

You can replace it with any birthday song you want.

For example:

```html
<audio id="bgMusic" src="audio/birthday-song.mp3" preload="auto" loop></audio>
```

Put your audio file inside the `audio` folder and update the filename in the HTML.

> ⚠️ If you're hosting the website publicly, make sure you have permission to use any copyrighted music you upload.

---

## 🎂 4. Change the Birthday Date

The current date displayed by the animation is:

```text
04 Sept
```

It can be changed inside the JavaScript:

```javascript
let datetxt = "04 Sept";
```

For example:

```javascript
let datetxt = "25 Dec";
```

---

## 📝 5. Customize the Sticky Notes

The scrapbook contains several notes that you can completely rewrite.

You can add:

* 💖 Personal messages
* 😂 Inside jokes
* 📸 Memories
* 🌸 Birthday wishes
* 🫶 Friendship messages
* 💌 Romantic messages

For example:

```text
Some people make life a little brighter just by being themselves.
```

Change it to something meaningful to your person.

---

## 💌 6. Customize the Birthday Letter

The envelope contains a longer personal message.

You can change the entire letter to your own message.

For example, you could write about:

```text
How you met
↓
Your favorite memories
↓
Why they're special
↓
A personal birthday wish
↓
A final surprise message
```

This is probably the best place to make the website feel **truly personal**.

---

# 🚀 How to Deploy

Once you've customized the website, you can host it for free.

## ⭐ Option 1 — Vercel

**Recommended**

[Vercel](https://vercel.com/) makes deployment extremely easy.

### Step 1

Create an account on Vercel using your GitHub account.

### Step 2

Upload/push your customized project to GitHub.

### Step 3

In Vercel:

**Add New → Project**

Select your GitHub repository.

### Step 4

Import the repository.

For this project, you generally don't need complicated build settings because it's a simple HTML/CSS/JavaScript website.

Click:

**Deploy 🚀**

After deployment, Vercel will provide a public link.

You can then send that link to your special person. 🎁

---

# 🐙 Option 2 — GitHub Pages

You can also host the website directly from GitHub for free.

### 1. Push the project to GitHub

Make sure your repository contains the HTML file along with the required folders:

```text
special-birthday-website/
│
├── index.html
├── style.css
│
├── images/
│   ├── ...
│
└── audio/
    └── birthday-song.mp3
```

### 2. Open your repository

Go to:

**Settings → Pages**

### 3. Configure GitHub Pages

Select:

```text
Deploy from a branch
```

Then select:

```text
main
/
(root)
```

and save.

GitHub will automatically deploy your website.

Your website will look something like:

```text
https://your-username.github.io/special-birthday-website/
```

---

# 🛠️ Tech Used

* HTML5
* CSS3
* JavaScript
* jQuery
* Font Awesome
* Google Fonts

---

# 🎁 Quick Customization Checklist

Before sending the website to your special person:

* [ ] Change **Maria** to her/his name
* [ ] Replace the main photo
* [ ] Replace the scrapbook photos
* [ ] Add your birthday song
* [ ] Change the birthday date
* [ ] Customize the sticky notes
* [ ] Rewrite the birthday letter
* [ ] Test everything on mobile
* [ ] Test the music
* [ ] Deploy the website
* [ ] Send the surprise link 🎂💖

---

# 💡 The Idea Behind This Project

This project was created for one simple reason:

> **Sometimes a small effort can become a big memory. ❤️**

Instead of sending another normal:

**"Happy Birthday 🎂"**

make them open a link and discover an entire little world made just for them. 🌸✨

Add their photos.

Add their favorite song.

Write something only they would understand.

And then send them the link.

That's the whole point of this project. 💖

---

## ⭐ Like the Project?

If you found this project useful:

⭐ Star the repository
🍴 Fork it
🎨 Customize it
🎁 Surprise someone

If you create your own version, feel free to share it!

---

### Made with ❤️, JavaScript & a little birthday magic ✨

**Curie X** [Website link](https://shahadathossain.in/)
