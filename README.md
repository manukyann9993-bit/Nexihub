# Running Nexihab Website Locally

The form submission requires the website to be served through a web server (not just opened as a file).

## Option 1: Python Simple HTTP Server (Easiest)

If you have Python installed, run this command in the Nexihab folder:

```bash
# Python 3
python -m http.server 8000

# Then open: http://localhost:8000
```

## Option 2: Node.js Live Server

If you have Node.js installed:

```bash
# Install live-server globally
npm install -g live-server

# Run in the Nexihab folder
live-server

# It will automatically open in your browser
```

## Option 3: VS Code Live Server Extension

1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Testing the Form

Once running on a local server, the FormSubmit form will work properly. Remember:
- First submission will send a confirmation email to nexihab.arm.suppteam@gmail.com
- Click the confirmation link in that email
- After that, all form submissions will be delivered automatically
