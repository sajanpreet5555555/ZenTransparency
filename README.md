
# Zen Browser Transparency Guide

> *Note: On macOS, you might only need the CSS and can skip Step 1 But i do not have a mac and cannot vouch for that*

## Make the Browser Transparent

1. Install MicaForEveryone [(Link)](https://github.com/MicaForEveryone/MicaForEveryone) - You will need to install .NET Core for this.

2. Set the Backdrop:

   Open MicaForEveryone and set the backdrop as `acrylic` globally.    
   (or create an exclusive rule for just Zen)
   
   ![image](https://github.com/user-attachments/assets/919c73e9-afdb-4981-a9fe-5f6278c7fd05)


4. Configure Zen: Go to ['about:config'](about:config) in Zen and set:
   - `widget.windows.mica` to `true`
   - `browser.tabs.allow\_transparent\_browser` to `true`
   - Enable workspaces for this to take effect.

## Make Websites Transparent

There are 3 stylesheets
   - General - Will be applied to any website.
   - Youtube & Google - These stylesheets are specifically optimized & looks better than the general stylesheet

### Adding the CSS:

   - Option 1: Using the [Stylus extension](https://addons.mozilla.org/en-US/firefox/addon/styl-us/):
      1. Open the Stylus settings page.

         ![image](https://github.com/user-attachments/assets/9ae71c16-09ea-4f35-8e70-840f88b44d07)

      3. click on "Write new style," and paste the styles. Do this thrice for the three styles.

         ![image](https://github.com/user-attachments/assets/a3b384ba-40e1-4f2e-bfd0-e27d1adf71cc)

  - Option 2: Directly paste all the CSS in `usercontent.css`.



## Make the New Tab Page Transparent
   
   1. Go to `about:profiles` in Zen
   
   2. Open the `Root Directory > chrome`
   
   3. Paste the stylesheets in `userContent.css`

## Screenshots
![image](https://github.com/user-attachments/assets/be8d69a8-ec84-4692-aef9-19436eb98f2c)
![image](https://github.com/user-attachments/assets/23bc4a2d-43e2-4c25-b54a-347ccfcc0a26)
![image](https://github.com/user-attachments/assets/24bc6872-a468-404c-8eb0-6d0251ff40bd)
![image](https://github.com/user-attachments/assets/a0895238-06ce-4169-8415-920d4a072ed2)
