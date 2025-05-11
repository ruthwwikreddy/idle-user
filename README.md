# 💤 Idle User Engagement Script

This project adds subtle and playful idle-user engagement to your webpage using JavaScript, CSS, and optional sounds.

It includes:

- 👀 Title animation when the user switches tabs
- 💬 Quotes that appear when the user is idle for 30+ seconds
- 🔊 Sound effects for engagement

---

## 📂 Files Included

- `index.html`: Main file where the script lives (you can also embed it in your existing page)
- `style`: CSS block for the floating quote bubble
- `script`: JavaScript that handles idle detection, tab switching, and quote logic

---

## 🔧 How It Works

1. **Tab Change Detection**
   - When the user switches tabs (visibility changes), the title starts rotating through funny call-back phrases like:
     - "Come back, genius!"
     - "Innovation’s waiting!"
     - "You left brilliance!" etc.

2. **Idle Detection**
   - After 30 seconds of no mouse, scroll, or keyboard activity:
     - A floating quote appears in the bottom-right corner
     - It changes every 5 seconds with motivational or quirky tech-style quotes
     - Quotes include:
       - "💡 Innovation is the calling card of the future."
       - "⚡ Don’t just scroll, solve!"
       - "🎯 MVPs are made, not found." etc.

3. **Sound Effects**
   - On first page load: soft "button click" sound
   - When returning after 1 minute away: different "alert" sound plays

---

## 🧪 Customization

You can modify:

- `idleQuotes[]`: Add or remove your own motivational messages
- `callBackTitles[]`: Change the tab title messages
- Sound URLs: Use your own `.mp3` links if you want different sounds
- `setTimeout` / `setInterval` durations: Tweak idle and quote timing

---

## 🚀 How To Use

Just paste the following into your `<head>` or just before `</body>` in your HTML file:

```html
<!-- Include the CSS -->
<style>
  /* (paste full #idle-quote CSS here) */
</style>

<!-- Include the JavaScript -->
<script>
  /* (paste full JavaScript code here) */
</script>
