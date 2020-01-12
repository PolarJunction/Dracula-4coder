## Dracula - 4Coder Theme

This is a theme file for the 4coder editor - http://4coder.net/

Simply, download the repository to your computer and copy the theme-dracula.4coder file out into your 4coder/themes directory.

You can then edit your 4coder.config - default theme to "theme-dracula".

![Theme Preview](https://i.ibb.co/5kdfMkG/Dracula-4coder-Theme.png)

### Function Highlighting
In order to get the true Dracula experience you will need to make some adjustments to the customisation layer for proper function/struct highlighting.

The easiest way to get started is to download a complete example, see: https://github.com/Skytrias/4files

If you follow the instructions there to install the customisation, you can edit the file render_highlight.cpp
Lines 18/19.

Where we set: 

    static u32 FUNCTION_HIGHLIGHT_COLOR = 0xFF50fa7b;
    static u32 STRUCT_HIGHLIGHT_COLOR = 0xFF8be9fd;
    
Do a re-build and you should be ready to go.
