## Need a 404 for your website?

Consider this simple, light, but innovative page.

## What's innovative?

 - Very mobile friendly design (try resizing your browser!)
 - Has a link (eye) to the homepage of your site
 - The other eye does a best-guess redirect using the URL entered and Google's I'm Feeling Lucky search
   - It stays on your domain
 - I haven't seen other monster 404 messages...


## License?

The code is free to use under the MIT license.

## How to use?

Different servers have different ways to set up 404 pages.  You want to avoid redirects to a page
(e.g. on 404 redirect to /404.html), because the smart redirect won't work correctly.

For use with Apache, you must set the `ErrorDocument`.  
Create a directory called "404" in the document root (the same directory as your index.html).  Then put the index.html file, and js and css sub-directories into it.  

You'll need to add this line in your apache configuration, or a file called `.htaccess` in your document root.

    ErrorDocument /404/index.html

Restart your server, unless you used the `.htaccess` file, and type a random URL in the browser.  To try the best-guess feature, type a url similar to one on your site, and click the left -- or only on mobile devices -- eye.

## It's not working!

Send me an email at aboutscript@gmail.com.




