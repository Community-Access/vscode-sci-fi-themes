# VS Code Sci-Fi Thinking Phrases 🚀

Welcome to the galaxy of custom Copilot Chat thinking phrases! This repository contains fun, themed loading phrases for GitHub Copilot Chat in VS Code.

When Copilot is reasoning or calling tools, it displays loading text. This repo lets you replace those defaults with phrases from your favorite sci-fi universes.

## Quick Start

1. **Pick your theme** from the folders below
2. **Copy the settings** to your VS Code `settings.json`
3. **Restart VS Code** or reload the window
4. **Open Copilot Chat** (`Ctrl+Shift+I`) and watch the magic happen!

## Available Themes

### 🖖 Star Trek: Starfleet Edition
Navigate treacherous code with Starfleet precision. Phrases include:
- "Engaging warp drive..."
- "Running full diagnostic..."
- "Consulting the computer..."

**File:** `themes/star-trek-settings.json`

### 🌌 The Hitchhiker's Guide to the Galaxy
The answer is always 42, but first we must ask the right question. Phrases include:
- "Consulting the Infinite Improbability Drive..."
- "Calculating the answer to the Ultimate Question..."
- "Translating Babel fish neurons..."

**File:** `themes/hitchhikers-settings.json`

### ⚡ Star Wars: The Force Awakens
May the Code be with you. Phrases include:
- "Meditating in the Jedi Archives..."
- "Reading the ripples in the Force..."
- "Consulting the ancient Sith holocrons..."

**File:** `themes/star-wars-settings.json`

## How to Use in VS Code

### Method 1: Copy and Paste (Easiest for this Workshop)

1. **Open** `themes/[your-favorite]-settings.json` in this repo
2. **Copy** the entire `"chat.agent.thinking.phrases"` object
3. **Open** your VS Code `settings.json`:
   - `Ctrl+Shift+P` (Mac: `Cmd+Shift+P`)
   - Type "Preferences: Open User Settings (JSON)"
   - Press `Enter`
4. **Paste** the setting into your `settings.json`
5. **Reload** VS Code: `Ctrl+Shift+P` → "Developer: Reload Window"

### Method 2: Merge Settings (For the Curious)

If you already have `chat.agent.thinking.phrases` configured:

- Use `"mode": "append"` to add your custom phrases to the defaults
- Or use `"mode": "replace"` to completely replace the defaults

### Method 3: Use with Copilot (For Chapter 13)

Ask Copilot to add settings:
1. Open Copilot Chat: `Ctrl+Shift+I`
2. Ask: "Add the Star Trek thinking phrases to my VS Code settings.json"
3. Copilot shows the setting
4. Accept the suggestion and reload VS Code

## Create Your Own Theme

The format is simple:

```json
"chat.agent.thinking.phrases": {
  "mode": "replace",
  "phrases": [
    "Your custom phrase here...",
    "Another witty phrase...",
    "More geeky goodness..."
  ]
}
```

**Tips for great phrases:**
- Reference your favorite universe's lingo
- Keep them under 50 characters
- Make them sound like your code is doing something epic
- End with "..." for the loading effect

## What Happens When You Reload?

Once you restart VS Code, open Copilot Chat (`Ctrl+Shift+I` / Mac: `Cmd+Shift+I`) and ask it a question. While Copilot thinks, you'll see your custom phrases cycling through instead of the defaults!

### Example:
```
You: "How do I fix a broken link in Markdown?"

Copilot: [Meditating in the Jedi Archives...]
Copilot: [Reading the ripples in the Force...]
Copilot: [Consulting the ancient Sith holocrons...]

Copilot: **Here's how to fix that broken link...**
```

## Troubleshooting

**Q: The settings aren't taking effect.**  
A: Make sure you've reloaded VS Code. Use `Ctrl+Shift+P` → "Developer: Reload Window" and try again.

**Q: I see the default phrases instead of my custom ones.**  
A: Double-check that your `settings.json` was saved. Try adding a test phrase and reloading.

**Q: Can I mix themes?**  
A: Absolutely! Copy phrases from multiple themes into one `phrases` array and reload. May the Force + Logic be with you.

## For Workshop Instructors

**Chapter 11 Cloning Challenge:** Have students clone this repo and pick a theme to customize their VS Code experience.

**Chapter 13 Copilot Challenge:** Ask students to ask Copilot to create their own custom theme (Dune, Marvel, Studio Ghibli, whatever!).

## License

These silly phrases are free to use, modify, and remix. May your code always load with cosmic flair. 🌟
