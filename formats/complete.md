A paragraph is a simple line of text. For example these lines combined for a paragraph.

Here's another paragraph. Paragraph can be spanned over multiple lines.

A paragraph with lorem ipsum: 

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer a pellentesque felis, eget efficitur velit. Phasellus diam velit, suscipit vel accumsan at, molestie sit amet est. In malesuada porta diam eu bibendum. Nam vestibulum nunc sit amet purus molestie, in ultricies velit blandit. In vitae metus id dolor tristique aliquam nec sit amet dolor. Ut a suscipit ex. Nullam porttitor maximus justo et gravida. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce ex magna, facilisis sollicitudin eros ac, suscipit porttitor turpis. Nulla tristique dolor sed libero commodo condimentum.

Aenean condimentum eros turpis, in euismod leo tincidunt at. Donec vulputate pellentesque felis vel consequat. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. In vitae fermentum sem. Aliquam id libero sed libero feugiat convallis non et erat. Vivamus eget maximus felis. Sed quis porta erat, nec pretium ipsum. Donec rutrum dolor sed nisl mattis pharetra ut eu erat. Ut finibus justo at dui tincidunt, ut rutrum ipsum placerat. Nunc sit amet diam tempor, viverra nibh in, pretium lectus.

Headers:
Setext-style headers:

Heading 1
========

Heading 2
------------

atx-style headers:

# h1
## h2
### h3
#### h4
##### h5
###### h6

BlockQuote:
> This is going to be a block qoute.
>
> This is another paragraph inside block quote.
> 

Emphasis:
The text appears to be *emphasized* by asterisk(*).
The text appears to be _emphasized_ by underscore(_).

The text is going to have more **emphasis** now. It appears to be bold by double asterisks(**).
The text is going to have more __emphasis__ now. It appears to be bold by double underscores(__).

Lists:
Unordered lists are created as follows and uses *, + & - to generate different bullets.
Asterisk List:
*  Rose
*  Lily
*  Lotus
*  Jasmine

Plus List:
+  Football
+  Basketball
+  Volleyball
+  Cricket

Minus List:
-  Dog
-  Cat
-  Fish
-  Rabbit

Ordered List:
1. Books
2. Cars
3. Bikes
4. Trucks

Links:
Link to [Google](http://google.com)
Link to [Facebook](http://facebook.com "this is a title")

Reference type links to [Google][1], [Yahoo][2] & [Facebook][3]

[1]: http://google.com/ "Google"
[2]: http://yahoo.com/ "Yahoo"
[3]: http://facebook.com/ "Facebook"

Images:
In-line:
![Puppy 1](http://media.mydogspace.com.s3.amazonaws.com/wp-content/uploads/2013/08/puppy-500x350.jpg "Cute Puppy")

Reference Type:
![Puppy 2][pup]

[pup]: https://s-media-cache-ak0.pinimg.com/236x/fb/46/ac/fb46acb038b9b9b64725d232afcbc71f.jpg "Puppy 2"

Code:
In this line I would like to mention `<pre>` tag and also `<header>` and `<section>` tag.

In the coming paragraph I will write a complete **JavaScript** code block to print _"Hello World"_ in console.

	function sayHello() {
		console.log("Hello World");
	}
	sayHello();

Now I'm going to add **html** code to say _hello world_:

	<!DOCTYPE html>
	<html>
		<head><title>Say Hello</title></head>
		<body>
			<p>Hello World!</p>
		</body>
	</html>