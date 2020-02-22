<strong>The Past, Present and Future of Local Storage for Web Applications</strong>

Local Storage is a type of web storage that allows websites and apps to store and access data right in the browser with no expiration date. This means the data stored in the browser will persist even after the browser window has been closed. The Local Storage and Session Storage properties allow to save key/value pairs in a web browser. 

Cookies were invented early stage of the web’s history, and they can be used for persistent local storage of small amounts of data. But they have these drawbacks:

	Cookies are included with every HTTP request, which slows down the web application by needlessly transmitting the same data over and over

	Cookies are included with every HTTP request, which sends data unencrypted over the internet (unless if you use SSL)

	Cookies are limited to about 4 KB of data — enough to slow down your application but not enough to be terribly useful

But what were necessary were followings:

	More storage spaces

	on the client

	Persistent beyond a page refresh

	And not transmitted to the server

Before the HTML5 Storage was introduced, various companies like Adobe, Google already had worked on local storage. But it was not meeting the expectation. Article defines HTML5 Storage as a way for web pages to store named key/value pairs locally, within the client web browser. Just like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server unless you go out of your way to send it manually. Unlike all previous attempts, at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not. So how do we use HTML5 Storage? Here is a simple look below:

interface Storage {

  getter any getItem(in DOMString key;
  
  setter creator void setItem(in DOMString key, in any data;
  
};

Calling setItem() with a named key that already exists will silently overwrite the previous value. Calling getItem() with a non-existent key will return null rather than throw an exception.

You can also track the changes to the HTML5 Storage area. One thing you can not forget is that some of the browsers may have certain limitations in term of HTML5 Storage.
