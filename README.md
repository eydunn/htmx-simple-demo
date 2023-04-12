# Simple htmx example
# 

See: https://htmx.org/ for more information.

Try to run the example:

    $ docker run -it -v "$(pwd)":/usr/share/nginx/html:ro -p 80:80 --rm nginx

Then open http://localhost/ in your browser.

You should see a H2 header. Press play on the video. Then a click on the header will send an AJAX request to the server, which will respond with a replacement H3 header. The new header will be inserted into the page. The video will run without interruption. The url will change to the value of the `hx-push-url` attribute. The browser history will be updated.



Or just try it at: https://eydunn.github.io/htmx-simple-demo/
