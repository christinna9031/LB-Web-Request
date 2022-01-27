# LB Web Request
A simple LioranBoard extension for web requests.    
You can choose type, whether to save the response in a variable and whether to enable proxy (for any cors errors).  
As of now it cannot pass custom headers or parameters except for query string.   
Might be useful for triggering actions without actually having to open the url in your browser or retrieving data from some public APIs.     
MrWaldo's update: An expression field that can be used to specify an JSON Path expression. In case of a single match a variable is set and in case of multiple matches a stack is created.         
The premade button shows how to retrieve the most recent tweet from NYTimes.

Note: *Proxy requires an API key. You can apply for your own key at https://grida.co/cloud/cors/register and replace the value of `headers['x-cors-grida-api-key']` with it.* 


**How to install an extension:**
1. Download the .lbe extension file from **Releases** section (please do not right click and save) 
2. Click on Install Extension in your LioranBoard Receiver
3. Select the extension file you downloaded 
4. Select your default Transmitter you are using. Make 100% sure it is the correct one. 
5. Refresh your Transmitter or close and reopen Lioranboard Receiver. 
6. Most extensions include a premade deck with buttons. If you do not see one, create a new button, add "Send to Extensions" command and select the extension you just installed. If you can only see the extension name with no input fields, it means it was not installed correctly. Repeat steps above.    

[![](https://github.com/christinna9031/LioranBoard-Files/blob/main/img/paypal.png?raw=true)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3YWXYQE3HKWHQ)

DISCLAIMER: The extension is provided as is. The developer has no obligation to provide maintenance and support services or handle any bug reports.
Feel free to edit the extension for your own use. You may not distribute, sell or publish it without the author’s permission.
