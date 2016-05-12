# Page-Load-Animation
An animation like pace.js to show before the page was completely loaded

I've used pace.js but the problem with pace was, the loading animation was shown after the page was completely loaded.

So, i have tried and made a solution, onclick every link on the page, jquery grabs and stops the event from the browser going direct to the link, and sends a ajax get request to that link. While the page is loading, it shows an animation on the current page. After the page is completely loaded, it replaces the whole current document with the received data and replaces the page url in the address bar.
