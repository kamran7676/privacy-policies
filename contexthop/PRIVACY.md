# Privacy Policy — ContextHop

ContextHop works on your machine.

- **Your conversations stay in your browser.** The extension reads the chat on
  the page you are viewing, converts it locally, and hands the result to you
  through the preview, clipboard, or a download. Conversations are never sent to
  ContextHop or any server we control.
- **No accounts, analytics, tracking, or remote code.** All logic ships inside
  the extension.
- **Claude usage.** On claude.ai the extension reads session and weekly usage
  from Claude's own responses and usage endpoint, using your existing session.
  This data travels only between your browser and claude.ai.
- **License checks.** If you activate ContextHop Pro, your license key is sent
  to the ContextHop site, which confirms the purchase with Paddle. Nothing else
  is sent.
- **Permissions:**
  - The content script loads on all http(s) pages so it can recognize supported
    chats, including self-hosted Open WebUI, which is detected by page structure.
    On pages it does not recognize it shows no UI and reads no content.
  - `clipboardWrite` copies a context pack or transcript when you press Copy.
  - `storage` keeps local usage counts, saved context packs, your pack
    instructions, and your license key. Removing the extension deletes them.
  - `activeTab` lets the toolbar popup work with the current tab.
