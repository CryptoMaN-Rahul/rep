# rep+

rep+ is a lightweight Chrome DevTools extension inspired by Burp Suite's Repeater. I often need to poke at a few requests without spinning up the full Burp stack, so I built this extension with the help of an LLM to keep my workflow fast and focused.

## What it does

- Captures every HTTP request you trigger while testing, listing them inside DevTools for easy inspection.
- Lets you replay any captured request and freely manipulate the raw method, path, headers, or body to probe endpoints for vulnerabilities.
- Provides power-user filters: search across URL, headers, and body, filter by method, or focus only on starred requests.
- Supports starring important requests, copying raw request/response blocks, and navigating back/forward through your edit history.

This combo makes rep+ handy for bug bounty hunters and vulnerability researchers who want Burp-like iteration without the heavyweight UI. Install the extension, open DevTools, head to the rep+ panel, and start hacking. 😎

### Demo
![Image](https://github.com/user-attachments/assets/a4767b2d-9246-4f69-a7cd-a99c05edc78e)
