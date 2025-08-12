# Alex Sidebar

Alex Sidebar is the AI assistant that integrates with Xcode to enhance your development experience. Powered by advanced AI models including Claude 3.5, GPT-4, and more, it helps you write better code faster than ever before.

## Key Features

- **Quick Actions (⌘ + L)**: Start chat about selected code for suggestions, documentation, and improvements
- **Command Palette (⌘ + K)**: Access inline completions
- **Smart Search (⌘ + P)**: Find anything in your codebase using natural language
- **Image to Code**: Drag & drop designs to generate corresponding UI code
- **Error Resolution**: One-click fixes for compiler errors and warnings
- **Customizable AI Models**: Choose from multiple AI providers or configure your own

## Installation

1. Download [AlexSideBar.dmg](https://github.com/DanielEdrisian/AlexSideBar-Public/releases/download/prod/AlexSideBar.dmg)
2. Drag Alex Sidebar to your Applications folder
3. Launch the app and follow the authentication prompts
4. The Xcode integration will initialize automatically

## Building Documentation

Our documentation is built using [Mintlify](https://mintlify.com). To preview locally:

1. Install the Mintlify CLI:

```bash
npm i -g mintlify
```

2. Run the development server:

```bash
mintlify dev
```

The documentation is automatically deployed when changes are pushed to the default branch. To make documentation changes:

1. Edit the relevant `.mdx` files in the docs directory
2. Preview changes locally using `mintlify dev`
3. Commit and push your changes

### Contributing

We welcome contributions to Alex Sidebar! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Documentation Changes

### Support Channels

- [Discord Community](https://discord.gg/T5zxfReEnd): Join for support, feedback, and tips
- [X](https://x.com/alexcodes_ai): Follow for updates
- Alex Bot: Tag @Alex in Discord to report bugs and request features
- Email: Contact team@alexcodes.app for direct support
- [Documentation Portal](https://www.alexcodes.app/docs): Access comprehensive guides

## Troubleshooting

- If `mintlify dev` isn't running, try `mintlify install` to reinstall dependencies
- For Xcode integration issues, try restarting Alex Sidebar
- Ensure you're running in a directory with `mint.json` for documentation preview

## Data Privacy

- No code storage or collection
- Opt-out of all third-party training data
- Minimal analytics collection (feature usage and diagnostics only)
- Local storage prioritization

## Folder Access Permissions

Before using Alex Sidebar with your exported projects, you'll need to grant access to specific folders where your projects are stored. This ensures Alex Sidebar can properly analyze and provide context for your files.

### Granting Folder Access

When you first attempt to open a project, Alex Sidebar will request permission to access folders like Desktop, Downloads, or Documents. 

> **Note**: If you accidentally dismiss the permission prompt, you can manually enable access through System Settings.

### Manual Permission Settings

If you need to update folder permissions later:

1. Click the Apple menu () in the top-left corner
2. Select **System Settings**
3. Click **Privacy & Security** in the sidebar
4. Scroll to **Files and Folders**
5. Locate **Alex Sidebar** in the list
6. Enable access for the folders you want Alex Sidebar to access:
   - Desktop
   - Documents
   - Downloads

[Image: folder_permissions_light.png]
[Image: folder_permissions_dark.png]

> **Important**: Without proper folder access, Alex Sidebar won't be able to analyze your project files or provide relevant context during your development workflow.
