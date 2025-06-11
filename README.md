# Zen Browser Error Pages Customization

## Quick Start
1. `./zen_customizer.sh extract` - Get the files
2. Edit files in the organized directories
3. `./zen_customizer.sh apply` - Apply changes

## Key Files to Edit
- **content/global/aboutNetError.html** - Main error page layout
- **skin/css/aboutNetError.css** - Error page styling
- **localization/en-US/neterror/netError.ftl** - Error message text

## Directory Structure
```
content/global/          # HTML and JavaScript files
skin/css/               # CSS styling files
skin/icons/             # Error icons
localization/en-US/     # Error message text
backups/                # Automatic backups
```

## Testing
Use `./zen_customizer.sh test` to make obvious changes, then apply them.
Always restart Zen Browser completely after applying changes.
