# CSS Smooth Scrolling Study

## 🌟 Project Goal

This is a focused study project to demonstrate how to achieve **smooth scrolling** between anchor links in a webpage using just **one line of CSS**: `scroll-behavior: smooth;`.

The project structure includes a fixed navigation bar that links to different full-height sections (`100vh`), clearly illustrating the smooth transition when clicking a link.

---

## 🛠️ Key Technology

The core functionality of this demo is implemented with a single CSS declaration:

```css
html {
    scroll-behavior: smooth;
}
```

## ⚠️ Troubleshooting (Smooth Scroll Not Working)
If you find that the scroll behavior is not smooth and the page is jumping instantly between sections, your browser might have an internal setting that needs to be enabled.

To ensure Smooth Scrolling is enabled in Chromium-based browsers (Chrome, Edge, Brave, etc.):

- Open a new tab and paste the following into the address bar:
- chrome://flags/#smooth-scrolling
- Find the setting named "Smooth Scrolling" or similar.
- Set its value to "Enabled".
- Relaunch your browser when prompted.

## 💡 Tutorial Reference
[Smooth scrolling with one line of CSS | CSS Tips - 
Optimistic Web](https://www.youtube.com/watch?v=3r2dDBW2Nn0)
