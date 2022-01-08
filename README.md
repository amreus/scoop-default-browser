# scoop-default-browser

This is a Windows Registry script to register Scoop's Firefox app as the user's default browser.

You will of course need to replace `_USERNAME_` with your actual user name.

Once these settings are merged into the Registry, the user must manually select "Scoop Firefox" from the Default Apps settings page.

In Windows, the default apps settings can be opened on the command line using:

     control /name Microsoft.DefaultPrograms /page pageDefaultProgram
     
# References

https://kolbi.cz/blog/2019/01/27/register-a-portable-browser-and-make-it-the-default
