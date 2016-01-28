=The uHttplib module=provides easy interface for fetching data across the Internet. Basically it implements the HTTP and HTTPS.  Otherwise process and parse HTML is the most useful function, it could convert html into element tree.

# Why I develop this library? #
Because there are many PHP\_MOUDLES that can do equal job like PHP\_CURL or PHP\_HTTP.
There are 3 reasons:

**1.	Almost PHP hosts or clouds provide PHP function without PHP\_HTTP or PHP\_CURL or additional modules. It’s quite difficult to compile with yourself.**2.	There is no Cookie ability in PHP\_HTTP module. If you want to use cookie or session, it’s useless.
**3.	Among standard PHP module, you can’t find a good lib to process HTML.**

## So uhttplib’s features are very powerful. ##

**1.	Cookie and Session capability**2.	Processing and Parsing function
**3.	GET/POST method can launch a http request**4.	Without additional module like PHP\_CURL,PHP\_HTTP

About me, I am a communication engineer in Shanghai and familiar with many programming languages. This library arouses from Python urllib2 and lxml module. If you intend to create a crawler with PHP,  uhttplib is fit for you. Enjoy it. Contact wu.qunfei@gmail.com