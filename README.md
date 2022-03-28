# HideOutliningMargin
Hides the Outlining margin in the Visual Studio code editor.

The Outlining margin is the one that expands and collapses all the regions, paired tags and code elements. It adds quite a lot of visual clutter to the editor and it also makes the left hand margin very wide which makes it harder to tell where the beginning of each line is.

Although it can be disabled for some editors (e.g. C#) for other editors there doesn't appear to be any way to remove it (e.g. HTML, C++).

This is a simple two line VSIX extension that removes the margin but leaves the Outlining functionality enabled, so it removes all the visual clutter while you are still able to expand and collapse all the sections using either the context menu or keyboard shortcut.
