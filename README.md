# Grid-Magazine

Hosted Link:- https://lok-ii.github.io/Grid-Magazine/


![Screenshot 2023-08-26 192202](https://github.com/Lok-ii/Grid-Magazine/assets/129180844/76bf5ee5-6a3c-4f0d-9dcc-535cdd3ceb0c)

	Element: <section class="heading">
		This element represents the main heading section of the webpage.
		
		Tags and Attributes:
		
		<section>: This tag defines a section of the document.
		class="heading": The class attribute assigns the CSS class "heading" to this section, allowing targeted styling.
		
		This section contains the main heading content, including the hero image, title, subtitle, author details, and social media icons.
		
  	Corresponding CSS Properties:
		
		.heading: The CSS class is used to style this section.
		grid-column: 2 / 3;: Positions this section in the center column of the main grid.
		display: grid;, grid-template-columns: repeat(2, 1fr);, row-gap: 1.5rem;: Sets up a grid layout for the section's content with 2 equally sized columns and vertical spacing.
		.hero: The CSS class styles the header (hero) part of this section.
		.hero-img: Styles the hero image within the header.
		grid-column: 1 / -1;: Spans the full width of the grid.
		position: relative;: Provides a positioning context for child elements.
		.hero-title, .hero-subtitle: Styles the title and subtitle within the hero.
		.author: Styles the author details.
		.author-name a:hover: Changes the background color when hovering over the author's name link.
		.publish-date: Styles the publish date.

		These CSS properties contribute to the visual layout, alignment, and styling of the heading section.

![Screenshot 2023-08-26 192221](https://github.com/Lok-ii/Grid-Magazine/assets/129180844/1e735d4f-1685-4375-9b68-e27278d8a8a1)


	Element: <section class="text">
		This element represents the main text content section of the webpage.
		
		Tags and Attributes:
		
		<section>: Defines a section of the document.
		class="text": Assigns the CSS class "text" to this section for styling.
		
		This section contains the main textual content describing the changes in the curriculum.
  
	Corresponding CSS Properties:
		
		.text: The CSS class styles this section.
		grid-column: 2 / 3;: Positions this section in the center column of the main grid.
		font-size: 1.8rem;, letter-spacing: 0.6px;, column-width: 25rem;, text-align: justify;: Sets the font size, letter spacing, column width, and text alignment for the text content.
		.first-paragraph::first-letter: Styles the first letter of the first paragraph with a larger font size and color.
		
  		These CSS properties define the typography and layout of the main text content section.

![Screenshot 2023-08-26 192240](https://github.com/Lok-ii/Grid-Magazine/assets/129180844/2b160038-2d0f-4184-b8bd-bb1925b75cd6)
![Screenshot 2023-08-26 192249](https://github.com/Lok-ii/Grid-Magazine/assets/129180844/df8191c7-e429-416d-80cf-641bce0ee9f7)

  	Element: <section class="text text-with-images">
		This element represents a section with text content and images.
		
		Tags and Attributes:
		
		<section>: Defines a section of the document.
		class="text text-with-images": Combines both "text" and "text-with-images" CSS classes for styling.
		
		
  		This section contains text content and images describing the history of the curriculum.
	
 	Corresponding CSS Properties:
		
		.text-with-images: The CSS class styles this section.
		display: grid;, grid-template-columns: 1fr 2fr;, column-gap: 3rem;, margin-bottom: 3rem;: Sets up a grid layout with two columns and spacing for text and images.
		.brief-history: The CSS class styles the article containing the brief history.
		.list-title, .list-subtitle: Styles the list titles and subtitles.
		.image-wrapper: The CSS class styles the image container.
		.image-1, .image-3: Styles the images.
		.image-quote: Styles the blockquote containing the image quote.
		
  		These CSS properties control the arrangement and styling of the text and image combination in this section.
		
	Corresponding CSS Properties (Selected):
		
		font-size: 62.5%;: Sets the base font size to 62.5% of the default size.
		background-color: rgb(20, 30, 40);: Sets the background color of the body.
		h1, h2, h3, h4, h5, h6: Define font families for different heading levels.
		text-decoration: none;, color: linen;: Sets link styles.
		display: grid;, grid-template-columns: minmax(2rem, 1fr) minmax(min-content, 94rem) minmax(2rem, 1fr);: Creates a three-column grid layout.
		
  
  		Media Queries: Adjusts layout and typography based on screen width.
			For example, at widths below 720px, the layout and image alignment change.
			At widths below 600px, the text with images becomes a single column.
		
  		These CSS properties control the overall styling and responsiveness of the webpage.
 

  
