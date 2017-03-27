
jQuery.com lists jQuery as a "fast, small, and feature-rich JavaScript library." It allows event handling, animation and Ajax (Asynchronous JavaScript and XML) via a simple to use API.  This blog post will run through some of the basics of jQuery and include  some examples that will hopefully provide for an even greater understanding of this tool.

Within jQuery are a several core features that are designed to streamline tasks by reducing the amount written code. This post will briefly discuss three of them, including: DOM traversal and manipulation, event handling and Ajax. It is important to note that since jQuery is a JavaScript library, it best to have a a good foundational knowledge of not only JavaScript itself but also HTML and CSS as well.

To start  off, you need to add jQuery as a dependency into your project. There are two ways to get this done, either via local installation or a CDN based version. The first option involves navigating to the jQuery website and downloading the latest version to your machine and then storing that file in a directory for the project you're working on. Then you would  You can then include the jQuery in your html, as shown in the following example:

```
<html>

   <head>
      <title>jQuery Local Installation</title>
      <script src = '/jquery/jquery-3.2.0.min.js'></script>

      <script type = 'text/javascript'>
         $(document).ready(function(){
            document.write('Hey, whats good?');
         });
      </script>		
   </head>

   <body>
      <h1>Heyo!</h1>
   </body>

</html>
```
The other option is to use the jQuery with a Content Delivery Network. This allows you to include jQuery library into your HTML code via a network of servers that deliver the content to you, thus eliminating the need to download it directly to your machine. Below is an example of HTML that includes a Google CDN version of the library:

```
<html>

   <head>
      <title>jQuery CDN Based Version</title>
      <script src='https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js'></script>

      <script type = 'text/javascript'>
         $(document).ready(function(){
            document.write('Hey, whats good?');
         });
      </script>
   </head>

   <body>
      <h1>Heyo!</h1>
   </body>

</html>

```
Once these examples are run, they will produce the result of `Hey, what's good?`.



```
let function runningMan(run) {

}
```

Resources:
http://jquery.com/
https://www.tutorialspoint.com/jquery/jquery-overview.htm
https://learn.jquery.com/about-jquery/
https://developers.google.com/speed/libraries/#jquery
