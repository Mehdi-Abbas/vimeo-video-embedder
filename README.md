# 🎥 Embed Video Referrer Updater

This is a simple and efficient web-based tool that helps you **add or update the `referrerpolicy="strict-origin"` attribute** in any video embed `<iframe>` code. It improves user privacy and is particularly useful when embedding videos from external sources like YouTube or Vimeo.

## 🔐 Why Use `referrerpolicy="strict-origin"`?

Setting `referrerpolicy="strict-origin"` prevents the full URL (including query parameters) from being sent to the embedded site's server. Only the origin (e.g., `https://example.com`) is shared, helping protect user privacy and limit data leaks.

## 🧠 How It Works

1. Paste any `<iframe>` embed code in the input box.
2. Click **Update Code**.
3. The tool automatically:
   - Adds `referrerpolicy="strict-origin"` if it's missing.
   - Updates any existing `referrerpolicy` to `"strict-origin"`.
4. Click **Copy Updated Code** to grab the result.

## 💡 Example Input

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/xyz123" frameborder="0" allowfullscreen></iframe>
