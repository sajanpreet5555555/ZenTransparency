
**Procedure for Making Your Browser Transparent (Windows)**
**Users on 1.8 and beyond see footnote**

*Note: MicaforEveryone is win11 exclusive, win 10 dosen't support neither mica nor acrylic the two effects zen supports*
*Note: On macOS, you might only need the CSS and can skip Step 1 But i do not have a mac and cannot vouch for that*



Step 1: Make the Browser Transparent

1. Install MicaForEveryone: You will need to install .NET Core for this.

   \- [MicaForEveryone download link](https://github.com/MicaForEveryone/MicaForEveryone)

2. Set the Backdrop:

   \- Open Zen click on the MicaForEveryone taskbar icon, select backdrop and select acrylic or mica\`

4. Configure Zen:

   \- Go to \`about:config\` in Zen and set:

   \- \`widget.windows.mica\` to \`true\`

   \- \`browser.tabs.allow\_transparent\_browser\` to \`true\`

   \- Enable workspaces for this to take effect.

 Step 2: Make Websites Transparent



I have written four styles to achieve this: one for YouTube,one for YTmusic, one for Google, and one that makes the background on all websites transparent. The YouTube and Google styles look great, but the general style may mess up some sites and might not work on others. You can choose if you want the general style or not.



Adding the CSS:

   \- Option 1: Install the extension Stylus:

\- [https://addons.mozilla.org/en-US/firefox/addon/styl-us/](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)

\- Open the Stylus settings page, click on "Write new style," and paste the styles. Do this thrice for the three styles.

   \- Option 2: Directly paste all the CSS in \`usercontent.css\`.



 Step 3: Make the New Tab Page Transparent

1. Go to \`about:profiles\` in Zen.

2. Open the root directory folder > \`chrome\`.

3. Paste the file \`userContent.css\`

<details>
   <summary>Screenshots</summary>

<div>

![image](https://github.com/user-attachments/assets/753872e8-b90f-4fed-ad77-c0a28982d9c4)

![image](https://github.com/user-attachments/assets/454c5a12-eafc-4b01-bcc7-cb3b4e548848)

![image](https://github.com/user-attachments/assets/7dc26988-7c81-4d71-9823-31c355889ecc)

![image](https://github.com/user-attachments/assets/c19ad435-ebdc-4e7e-870f-adba0dfab678)

![image](https://github.com/user-attachments/assets/40e64b4d-dcbb-4f6e-997d-dab89755eab3)

![image](https://github.com/user-attachments/assets/e499fb25-f518-4ce9-85a3-17669da2b78b)

</div>
</details>
1.8 and above:
Since zen has reworked transparency you have to do 2 extra things
 
1: Increase transparency

1. Go to \`about:profiles\` in Zen.

2. Open the root directory folder > \`chrome\`.

3. Make a file called \`userChrome.css\` and paste this in it
   <code>:root {#browser{background: rgba(199, 227, 239, 0.11) !important;}}</code>
