# AI Site Chat — example

A floating chat bubble that answers visitor questions using your own indexed page content. When it cannot answer, the visitor can leave a name, email and question instead of hitting a dead end.

One script tag. No signup for your visitors.

## Quick start

```html
<script async src="https://feed-pulse.com/api/embed/ask-site.js?site_id=YOUR_SITE_ID"></script>
Get a site ID at https://feed-pulse.com — free, no card.

Options
Param	Values	Default
pos	br, bl, tr, tl	br
size	sm, md, lg	md
anim	none, pulse, bounce, sparkle, glow	pulse
theme	indigo, obsidian, ivory, sunset and more	indigo
Bottom-left, dark, no animation:

<script async src="https://feed-pulse.com/api/embed/ask-site.js?site_id=YOUR_SITE_ID&pos=bl&theme=obsidian&anim=none"></script>
How answers are produced
Answers come from your site's own indexed page content, not from general world knowledge, so the bubble will say it does not know rather than inventing an answer about your product. Unanswered questions are captured as a lead with the visitor's consent.

Live customizer
https://feed-pulse.com/free-ai-site-chat

License
MIT


**Commit changes**.

## Step 3.3 — Add index.html

**Add file ▾ → Create new file**, filename `index.html`, paste:

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>AI Site Chat — example</title>
  <style>
    body { font-family: ui-sans-serif, system-ui, sans-serif; max-width: 42rem; margin: 4rem auto; padding: 0 1.5rem; line-height: 1.6; }
    h1 { font-size: 1.5rem; margin-bottom: .25rem; }
    p { color: #555; }
  </style>
</head>
<body>
  <h1>AI Site Chat</h1>
  <p>Look for the chat bubble in the corner. It answers from indexed page content.</p>
  <p>Replace <code>site_id=demo</code> with your own.
     Positions and themes: <a href="https://feed-pulse.com/free-ai-site-chat">customizer</a>.</p>

  <script async src="https://feed-pulse.com/api/embed/ask-site.js?site_id=demo"></script>
</body>
</html>
