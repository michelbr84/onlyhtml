# Clean and elegant **Hello World** web page built with **one single HTML file** (no external dependencies).  
It includes modern CSS styling, subtle interactive effects, and JavaScript-powered UI behavior.


---

### 🔥 Features


- **Single file**: Everything lives in one `index.html`

- **Modern elegant UI**:
   - gradient background
   - frosted-glass card
   - subtle glow highlight based on mouse position
   - soft shadows and rounded corners

- **JavaScript interactions**:
   - "Say Hello" updates the greeting with a counter
   - "Show Time" prints the current time
   - "Copy Greeting" copies the greeting to clipboard (with fallback)
   - console/log panel that records actions with timestamps

- **Keyboard shortcuts**:
   - Press **H** to trigger "Say Hello"
   - Press **Ctrl + L** (or **Cmd + L** on macOS) to clear the log

- **Accessibility friendly**:
   - semantic structure
   - `aria-label` and `aria-live` log output


---

### 🏁 Project Structure


This project is intentionally minimal:


```

elegant-hello-world/
└── index.html

```


---

### 🚀 Getting Started


#### 1) Download / Create the file


Create a file named:


```

index.html

```


Then paste the provided HTML into it.


#### 2) Open it


You can run it with **no server at all**:


- Double-click `index.html`, or
- Right-click → open with your browser


It works on:


- Chrome
- Edge
- Firefox
- Safari


---


### 🧠 How It Works


#### UI Layout


The page displays a centered card containing:


- a title bar
- a hero section with buttons
- a "console log" panel
- a footer with a reset link


#### Console Log


Whenever a user interacts with the page, it adds lines like:


```

[18:42:10] Greeting updated "Hello, World!!" (count: 2)
[18:42:13] Copied to clipboard "Hello, World!!"

```


This is useful as a mini demo of event-driven UI programming.


---

### ⌨️ Keyboard Shortcuts


| Shortcut | Action |
|----------|--------|
| `H` | Say Hello |
| `Ctrl + L` / `Cmd + L` | Clear the console log |


---

### 🎨 Styling Notes


The page uses:


- CSS variables for theme consistency
- a layered background:
   - two radial gradients
   - a linear gradient
   - subtle grain overlay (SVG noise)

- glassmorphism effects:
   - translucent panels
   - borders and blur-like lighting

- hover/press animations on buttons


---


### ♿ Accessibility


The log panel is defined as:


- `role="log"`
- `aria-live="polite"`


So screen readers can announce updates without being too aggressive.


---

### 🎨 Customization


Here are some easy modifications you can make:


#### Change the default greeting


Find this line in the script:


```js

greeting: "Hello, World!",

```


Change it to:


```js

greeting: "Hello, Michel!",

```


#### Change the page title


In `<head>`:


```html

<title>Hello World</title>

```


#### Change accent colors


In CSS:


```css

--bg1: #0b1220;
--bg2: #070a12;

```


You can also adjust the glow colors inside:


```css

radial-gradient(... rgba(98,120,255,.22) ...)
radial-gradient(... rgba(255,120,220,.18) ...)

```


---


### 🧪 Browser Compatibility


Works in all modern browsers.


Clipboard API requires HTTPS or secure contexts in some browsers.


The fallback ensures the feature still works in most situations.


---

### 📝 License


This template is free to use for any purpose:


- personal projects
- portfolios
- demos
- templates


You may optionally include attribution, but it is not required.


---

### 🧑 Author


Created as an elegant single-file Hello World template with modern HTML/CSS/JS.

Change the background to green.