# Windows Registry UI Themes

This repository contains custom registry themes that transform your Windows user interface appearance. These themes modify various color settings in the Windows Registry to create a cohesive visual experience.

## Table of Contents
- [Themes Included](#themes-included)
- [Installation Instructions](#installation-instructions)
  - [Standard Method](#installation-instructions)
  - [Quick Install Method](#quick-install-method)
- [Backing Up Current Theme](#backing-up-current-theme)
- [Customization Tips](#customization-tips)
- [Reverting Changes](#reverting-changes)
- [Compatibility](#compatibility)
- [Screenshots](#screenshots)
- [Contributing](#contributing)

## Themes Included

### Dark Crimson (formerly test.reg)
A sophisticated dark red/burgundy theme with:
- Rich, deep red window backgrounds (35 20 20)
- High-contrast white text elements
- Crimson accents and highlights (180 30 30)
- Dark mode enforcement across UI
- Custom transparency effects
- Consistent red tones across all UI elements

### Ruby Accent (formerly Red One.reg)
A standard light theme with elegant red accents:
- Maintains light window backgrounds (255 255 255)
- Black text for optimal readability
- Bold red highlights for interactive elements
- Striking red desktop background (179 13 27)
- Standard light UI with strategic red accents

## Installation Instructions

1. **Before installing**: Create a system restore point or backup your registry
   - Press Win+R, type `sysdm.cpl`, navigate to System Protection tab
   - Select your system drive and click "Create"

2. **Installing a theme**:
   - Download the desired .reg file
   - Right-click the file and select "Merge"
   - Confirm the registry modification prompt
   - Sign out and sign back in (or restart) to apply all changes

## Quick Install Method

For a faster installation:
1. Simply double-click any .reg file in File Explorer
2. Windows will prompt with a warning about modifying the registry
3. Click "Yes" to confirm and apply the theme
4. Log out and log back in to see all changes applied

## Backing Up Current Theme

Before installing a new theme, you may want to save your current color settings:

1. **Creating a registry backup**:
   - Press Win+R and type `regedit` to open Registry Editor
   - Navigate to `HKEY_CURRENT_USER\Control Panel\Colors`
   - Right-click on the Colors folder and select "Export"
   - Save the file as "MyCurrentColors.reg" for future restoration
   - Do the same for `HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\DWM` and `HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Accent`

2. **Restoring from backup**:
   - Simply double-click your saved .reg file whenever you want to restore those settings
   - Sign out and back in to see the changes fully applied

This method preserves your exact color preferences and makes it easy to switch between different themes.

## Customization Tips

- You can modify any RGB color values in the .reg files before importing
- Use a color picker tool to find your preferred colors
- Each value follows RGB format: "R G B" (values from 0-255)
- Edit accent colors to match your personal preference

## Reverting Changes

If you wish to return to the default Windows appearance:

1. **Using Settings**:
   - Open Settings > Personalization > Colors
   - Select default theme options 
   - Toggle "Dark mode" or "Light mode" as desired

2. **Registry Restoration**:
   - Use your previously created system restore point
   - Or use the Windows default theme .reg file included in the "defaults" folder

## Compatibility

- Fully tested on Windows 10 (all major versions)
- Mostly compatible with Windows 11 (some UI elements may vary)
- Works best with the default Windows theme as a starting point

## Screenshots

[Coming Soon! Screenshots will be added to show how each theme appears when applied]

## Contributing

Feel free to submit pull requests with your own theme creations or improvements to existing themes!