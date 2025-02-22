
**Procedure for Making Your Browser Transparent (Windows)**


*Note: MicaforEveryone is win11 exclusive, win 10 dosen't support neither mica nor acrylic the two effects zen supports*
*Note: On macOS, you might only need the CSS and can skip Step 1 But i do not have a mac and cannot vouch for that*



Step 1: Make the Browser Transparent

1. Install MicaForEveryone: You will need to install .NET Core for this.

   \- [MicaForEveryone download link](https://github.com/MicaForEveryone/MicaForEveryone)

2. Set the Backdrop:

   \- Open MicaForEveryone, click on the plus icon in the bottom left > \`Add Process Rule\` > type zen
Then set backdrop as acrylic and set the to toggle to the on position

![image](https://github.com/user-attachments/assets/2d8cc45b-ce34-4e54-8362-d8ecf698041c)

4. Configure Zen:

   \- Go to \`about:config\` in Zen and set:

   \- \`widget.windows.mica\` to \`true\`

   \- \`browser.tabs.allow\_transparent\_browser\` to \`true\`

   \- Enable workspaces for this to take effect.

 Step 2: Make Websites Transparent



I have written three styles to achieve this: one for YouTube, one for Google, and one that makes the background on all websites transparent. The YouTube and Google styles look great, but the general style may mess up some sites and might not work on others. You can choose if you want the general style or not.



Adding the CSS:

   \- Option 1: Install the extension Stylus:

\- [https://addons.mozilla.org/en-US/firefox/addon/styl-us/](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)

\- Open the Stylus settings page, click on "Write new style," and paste the styles. Do this thrice for the three styles.

   \- Option 2: Directly paste all the CSS in \`usercontent.css\`.



 Step 3: Make the New Tab Page Transparent

1. Go to \`about:profiles\` in Zen.

2. Open the root directory folder > \`chrome\`.

3. Paste the file \`userContent.css\`

Screenshots
![image](https://github.com/user-attachments/assets/be8d69a8-ec84-4692-aef9-19436eb98f2c)
![image](https://github.com/user-attachments/assets/23bc4a2d-43e2-4c25-b54a-347ccfcc0a26)
![image](https://github.com/user-attachments/assets/24bc6872-a468-404c-8eb0-6d0251ff40bd)
![image](https://github.com/user-attachments/assets/a0895238-06ce-4169-8415-920d4a072ed2)
