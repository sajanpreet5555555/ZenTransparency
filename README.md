**Procedure for Making Your Browser Transparent (Windows)**



*Note: On macOS, you might only need the CSS and can skip Step 1 But i do not have a mac and cannot vouch for that*



Step 1: Make the Browser Transparent

1. Install MicaForEveryone: You will need to install .NET Core for this.

   \- [MicaForEveryone download link](https://github.com/MicaForEveryone/MicaForEveryone)

2. Set the Backdrop:

   \- Open MicaForEveryone and set the backdrop as acrylic globally (or create an exclusive rule for just Zen).

3. Configure Zen:

   \- Go to \`about:config\` in Zen and set:

\- \`widget.windows.mica\` to \`true\`

\- \`browser.tabs.allow\_transparent\_browser\` to \`true\`

   \- Enable workspaces for this to take effect.

 Step 2: Make Websites Transparent



I have written three styles to achieve this: one for YouTube, one for Google, and one that makes the background on all websites transparent. The YouTube and Google styles look great, but the general style may mess up some sites and might not work on others. You can choose to add or exclude it if you want.



Adding the CSS:

   \- Option 1: Install the extension Stylus:

\- [https://addons.mozilla.org/en-US/firefox/addon/styl-us/](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)

\- Open the Stylus settings page, click on "Write new style," and paste the styles. Do this thrice for the three styles.

   \- Option 2: Directly paste all the CSS in \`usercontent.css\`.



 Step 3: Make the New Tab Page Transparent

1. Go to \`about:profiles\` in Zen.

2. Open the root directory folder > \`chrome\`.

3. Paste the file \`userContent.css\`


