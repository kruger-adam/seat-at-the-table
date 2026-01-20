# Seat at the Table - PROMETHEUS Chat Interface

A scripted fake AI chat interface for film production. The interface looks like a modern AI assistant but returns pre-scripted responses when actors type specific trigger lines.

## Quick Start

1. **Open the interface**: Just double-click `index.html` to open in any web browser
2. **Full-screen for filming**: Press `F11` (Windows) or `Cmd+Ctrl+F` (Mac) for full-screen mode
3. **Configure your script**: Click the "⚙ Script Editor" button in the top-right corner

## How It Works

The interface matches what the actor types against your configured "trigger" phrases. When a match is found, it displays the corresponding AI response with a realistic typing animation.

**Matching is flexible** - it doesn't require exact matches. The system will find the right response if:
- The input is similar to the trigger phrase
- Key words from the trigger are present
- The phrases are close enough

## Script Editor Features

Click **⚙ Script Editor** to open the configuration panel:

- **Add Script Lines**: Create trigger/response pairs
- **Timing Settings**: Adjust how long the AI "thinks" before responding and typing speed
- **Clear Chat**: Reset the conversation for another take

### Timing Controls

- **Thinking delay**: How long the typing indicator shows (default: 1500ms)
- **Typing speed**: Milliseconds per character (default: 25ms)

## Tips for Filming

1. **Test your script beforehand**: Run through all the lines to make sure triggers match
2. **Use the timing controls**: Slower typing can look more dramatic
3. **Clear chat between takes**: Keeps the interface clean for each shot
4. **Hide the Script Editor**: Close it before filming starts

## Customizing the Look

The interface is styled as "PROMETHEUS" - a fictional AI company. If you need to change:

- **Company name**: Edit the `<span class="brand-name">` in the HTML
- **Model version**: Edit the `<span class="brand-model">` text
- **Colors**: Modify the CSS variables at the top of the `<style>` section

## Default Example Lines

The interface comes with three example script lines. Edit or replace these in the Script Editor:

1. "What is consciousness?" → philosophical response about AI awareness
2. "Are you ready for the launch?" → response about deployment readiness
3. "Do you ever worry about the future?" → response about AI uncertainty

## Technical Notes

- Works offline - no internet connection required
- Scripts save automatically to browser storage
- Single HTML file - easy to copy and share
- Works on any modern browser (Chrome, Firefox, Safari, Edge)

---

*Created for "Seat at the Table" - an AI x-risk short film by Suzy Shepherd*

