# TME (Tomorrow Markdown Editor)

**Exclusively Customized for Typace**

A beautiful, feature-rich live Markdown editor with seamless Vercel deployment.

[Live Demo](https://tme.mrche.top) | [Typace Team](https://github.com/typace-team)

---

## Preview

![图片描述](https://ik.imagekit.io/terryzhang/IMG_7115.jpeg)

![图片描述](https://ik.imagekit.io/terryzhang/IMG_7116.jpeg)

![图片描述](https://ik.imagekit.io/terryzhang/IMG_7118.jpeg)

![图片描述](https://ik.imagekit.io/terryzhang/IMG_7114.jpeg)

## Features

TME is designed to provide a smooth, distraction-free writing experience with powerful built-in tools:

- **Live Preview**: Split-screen interface. Edit on the left, see instant rendering on the right.
- **Theme Switching**: Seamlessly toggle between Light and Dark modes to suit your environment.
- **Auto-Save**: Never lose your work. Content is automatically saved to your browser's local storage.
- **Syntax Highlighting**: Automatic code block highlighting for better readability.
- **One-Click Copy**: Quickly copy your raw Markdown or specific code blocks to the clipboard.
- **File Export**: Easily download and export your work as a standard `.md` file.
- **Quick Toolbar**: Click-to-insert buttons for common Markdown syntax (bold, headers, lists, etc.).
- **Responsive Design**: Fully optimized for desktops, tablets, and mobile screens.

## Quick Deployment

### Option 1: Deploy to Vercel (Recommended)

The fastest way to get your own instance of TME running.

**1. One-Click Deploy:**

Click the button below to instantly deploy to your Vercel account:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/typace-team/tme)

**2. Fork and Deploy (For Customization):**

If you want to modify the code before deploying:
1. **Fork** this repository to your own GitHub account.
2. Log in to [Vercel](https://vercel.com).
3. Click **Add New** -> **Project**.
4. Import your forked repository and click **Deploy**.
5. Wait a few seconds, and your custom editor will be live.

### Option 2: Run Locally

Since TME is built with pure HTML, CSS, and JavaScript, you do not need complex build tools. Just run a simple local server:

```bash
# 1. Clone the repository
git clone https://github.com/typace-team/tme.git

# 2. Navigate into the project directory
cd tme

# 3. Start a local server (Choose one)

# Using Python 3:
python3 -m http.server 8000

# Using Node.js (if you have http-server installed):
npx http-server -p 8000
```

Then, open your browser and visit `http://localhost:8000`.

## Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Hosting**: Vercel
- **Architecture**: No heavy frameworks. Lightweight, blazing fast, and zero dependencies.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

**Typace Team** | [GitHub Account](https://github.com/typace-team) | [Live Demo](https://tme.mrche.top)
