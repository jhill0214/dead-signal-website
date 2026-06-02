# Dead Signal - Rust Server Website

An eerie, paranormal-themed website for the Dead Signal Rust server. Built with pure HTML, CSS, and JavaScript for GitHub Pages deployment.

## Features

- **Dark, atmospheric design** with eerie red and purple color scheme
- **Paranormal theme** with glitch effects, fog overlay, and static noise
- **Server information** section with connection details
- **Player rankings** display (placeholder data - can be integrated with real server data)
- **Discord integration** with call-to-action buttons
- **Responsive design** that works on mobile and desktop
- **Smooth animations** and interactive elements

## Customization

### Server IP
Update the server IP in `index.html`:
```html
<p class="ip-address">connect deadsignal.rust.server:28015</p>
```
And in the JavaScript copy function:
```javascript
const ip = "connect deadsignal.rust.server:28015";
```

### Discord Invite
Replace `YOUR_DISCORD_INVITE` in `index.html` with your actual Discord invite code:
```html
<a href="https://discord.gg/YOUR_DISCORD_INVITE" target="_blank" class="btn discord-btn">
```

### Player Rankings
The rankings section currently has placeholder data. To integrate real server data, you can:
1. Use a Rust server API (like BattleMetrics) to fetch live data
2. Manually update the rankings in the HTML
3. Set up a backend service to sync data automatically

### Server Details
Update server-specific information in the Connect section:
- Max Players
- Map type
- Wipe Schedule
- Group Limit

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top-right corner
3. Select "New repository"
4. Name your repository (e.g., `dead-signal-website`)
5. Make it public (required for free GitHub Pages)
6. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. In your new repository, click "uploading an existing file"
2. Drag and drop all files from this project:
   - `index.html`
   - `styles.css`
   - `.nojekyll`
   - `README.md`
3. Click "Commit changes"

**Option B: Using Git Command Line**
```bash
cd C:\Users\Jamie\CascadeProjects\dead-signal-website
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/dead-signal-website.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. In the left sidebar, click "Pages"
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"

### Step 4: Access Your Website

After 1-2 minutes, your website will be live at:
```
https://YOUR_USERNAME.github.io/dead-signal-website/
```

## Custom Domain (Optional)

To use a custom domain (e.g., `deadsignal.com`):

1. Buy a domain from a registrar (Namecheap, GoDaddy, etc.)
2. In GitHub repository Settings > Pages, add your custom domain
3. Configure DNS settings at your registrar:
   - Add a CNAME record pointing to `YOUR_USERNAME.github.io`
4. Wait for DNS propagation (can take 24-48 hours)

## File Structure

```
dead-signal-website/
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── .nojekyll           # Disables Jekyll processing
└── README.md           # This file
```

## Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling, animations, and responsive design
- **JavaScript** - Interactive features (copy IP, smooth scrolling, parallax)
- **Google Fonts** - Creepster and Special Elite fonts for the eerie theme
- **GitHub Pages** - Free hosting

## Browser Support

- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

## Future Enhancements

- **Live server status** integration with Rust server APIs
- **Dynamic player rankings** from BattleMetrics or similar
- **Event calendar** for server events
- **News/updates section** for server announcements
- **Image gallery** for server screenshots
- **Contact form** for server inquiries

## Support

For issues or questions:
- Check the [GitHub Pages documentation](https://docs.github.com/en/pages)
- Review the code comments in `index.html` and `styles.css`

## License

This project is open source and available for the Dead Signal Rust server community.

---

**The Signal Never Dies.** 👁️
