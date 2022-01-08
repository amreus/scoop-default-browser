# scoop-default-browser

This is a Windows Registry script to register Scoop's Firefox app as the user's default browser.

***Although this script "works for me", I do not recommend using this script as-is - it is meant as an example or template***

***This script is specific to my user profile - you will need to modify to fit your needs!***

Once these settings are merged into the Registry, the user must manually select "Scoop Firefox" from the Default Apps settings page.

In Windows, the default apps settings can be opened on the command line using:

     control /name Microsoft.DefaultPrograms /page pageDefaultProgram
     

from https://kolbi.cz/blog/2019/01/27/register-a-portable-browser-and-make-it-the-default

# References

* A place to start. [Firefox NSIS Install Script](https://searchfox.org/mozilla-central/source/browser/installer/windows/nsis/shared.nsh#512)
