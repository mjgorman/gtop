# gtop
Server monitoring and administration, right from Google Glass.

<img src='http://okaysass.com/pics/gif/gtop_1.gif'>

<img src='http://okaysass.com/pics/gif/gtop_2.gif'>

<img src='http://okaysass.com/pics/gif/gtop_4.gif'>

Here are the [install instructions and more information](http://okaysass.com/posts/14-02-24-gtop-server-monitor-google-glass)

gtop is developed by Jonathan Warner, aka [Jaxbot](http://jaxbot.me/), and is provided as free, open source software, under the MIT license.

# More Howto:
Install Apache or nginx. You will need to proxypass the https:// subscription URL to the port your gtop is running on

ProxyPass /subscription http://example.com:8080/subscription

Suggest running via nohup node index & You can then capture node output to nohup file for easier troubleshooting. 
