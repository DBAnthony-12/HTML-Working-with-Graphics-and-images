# HTML-Working-with-Graphics-and-images
HTML Working with Graphics and Images
	Utilizing a range of elements and properties, working with graphics and images in HTML allows for the effective and efficient integration of visual material into web pages. The image's pixel size must also be disclosed to the browser. The size of the image in this instance is 400 pixels wide by 300 pixels tall. Use the width and height properties of the image element to include that information. It is sufficient to know only the numerical values for these quantities; the units are not required.
Image formats
	When placing an image on a webpage, the image file itself is an important factor to take into account. It must be in a file format that is compatible with most web browsers, and there are several choices. To ensure speedier download times and avoid customers using too much data, we want to decrease the quantity of data while still maintaining a high-quality image.
	GIF:
•	GIFs function effectively for combining illustrations with lots of the same colors, but they are not as effective at compressing photos.
	SVG:
•	In reality, SVG is a graphics programming language, and there are classes specifically for it. SVG files are treated the same as other online file types and can be exported from applications like Illustrator or Sketch.
	JPG:
•	Jpg is popular for compressing photographs. Most digital cameras save images in JPG format. By lowering color information, JPGs can be compressed even further, reaching a perfect conflict between file size and quality.
	PNG:
•	A more recent format called PNG is useful when you want transparency in a picture.
Responsive Images:
	Creating websites and applications that function well across a range of devices requires the use of responsive pictures, which make sure that images load quickly on smaller devices without compromising their quality on larger screens. This idea is essential for increasing online performance, decreasing load times, and optimizing the desktop, tablet, and smartphone user experiences.
	Size Attributes:
•	In order to help the browser choose which image to download, the sizes attribute in the <img> element collaborates with srcset to give it more information about how wide the picture will be at different viewport widths. 
•	Code:
	<img src="small.jpg"
	     srcset="medium.jpg 1000w, large.jpg 2000w"
	     sizes="(max-width: 600px) 480px, (max-width: 900px) 800px, 1200px"
	     alt="An example image">
	Picture element:
•	More control over which image resource loads is provided by the <picture> element. This allows different images to be delivered according to media queries, including multiple formats for browsers that support WebP, a more recent and efficient standard.
•	Code:
	<picture>
	  <source srcset="image.webp" type="image/webp">
	  <source srcset="image.jpg" type="image/jpeg">
	  <img src="image.jpg" alt="An example image">
	</picture>
Responsive Width:
	One of the most important aspects of current web development is creating a responsive design, where the layouts and elements change in width according to the screen size of the device viewing the page. CSS (Cascading Style Sheets) is usually utilized to produce responsive widths by utilizing a variety of attributes and approaches.
Responsive pictures:
	In web development, responsive design is essential to making sure websites work and look well across a range of devices and screen sizes. Since images are a major component of most websites, they require extra care to be responsive. In order to guarantee quick loading times and an excellent user experience on all device types, responsive pictures are about sending the correct image, at the appropriate size, to each user's device.

Fig caption and Figure:
	Semantic HTML5 elements like <figure> and <figcaption> are meant to improve page structure by adding additional meaning and accessibility for users and search engines alike. They are mostly used for adding images to webpages, such as pictures, code listings, diagrams, and illustrations, accompanied with a caption or description.
•	Figure: media like pictures, diagrams, code snippets, illustarions and so forth can be contained within the <figure> element with its caption (<figcaption>)
•	Figcaption: A caption or legend for the remaining contents of its parent <figure> element is provided by the <figcaption> element.
	To summarize, the HTML elements <figure> and <figcaption> possess significant power since they augment the semantic value of web content, facilitate accessibility, and provide increased authority over the display of media and its corresponding text.
