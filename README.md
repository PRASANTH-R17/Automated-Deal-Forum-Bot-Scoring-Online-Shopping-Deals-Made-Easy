# Welcome to Deal Forum Bot: Your Automated Shopping Assistant!
Hey there, I'm Prasanth, and I'm excited to introduce you to my creation—Deal Forum Bot. This bot is all about helping you score awesome deals while you sit back and relax.

**What's Deal Forum All About?**
Imagine having a smart buddy that scours the web for the best online shopping deals. That's exactly what Deal Forum does. But it goes beyond that! It also grabs key info about the products, like what's hot, where to get it, and even checks the price history.

**Meet Zara: Our 24/7 Sidekick**
Deal Forum Bot is a workhorse, tirelessly working around the clock. It needs a reliable sidekick, and that's where Zara comes in. Zara, my trusty home server, takes care of Deal Forum and does other cool things like blocking ads, acting as a VPN server, and more.

**What's Inside This Repository?**
Here, I'm sharing the story behind Deal Forum Bot and how I tackled some challenges:

**Navigating the Web Scraping Maze**
The internet can be tricky to navigate, especially when it comes to getting info from websites like Amazon and Flipkart. I tried a library called BeautifulSoup, but it had limitations. So I switched gears and went for Selenium—a versatile tool. But it had its own quirk: it liked incognito mode. With some clever tricks using Chrome Debugging, I made it work my way.

**Why Regular Browsers Are Cool**
Regular browsers became my secret weapon. They store my account info and bypass some website restrictions. This means smoother operation and no need to set up everything from scratch.

**Unleashing Selenium's Power**
Selenium is known for testing, but I turned it into a data-fetching powerhouse. By targeting specific HTML elements, I could snag essential data like product names, prices, images, and links.

**Unveiling Price History**
I wasn't stopping at just basic details. I wanted to show the price history too. I found a great site, "https://pricehistory.app/", and used Selenium to gather this insightful info.

**Short Titles, Big Impact**
Long product titles can be a mouthful. I wanted to make them snappier. After trying out various AI solutions, I settled on ChatGPT. It wasn't without its challenges, but I tamed it using Selenium. The result? Short and sweet product titles.

**Image Magic**
Visuals matter. I made sure to include product images. With Selenium's help, I grabbed image URLs. The urllib and os libraries handled downloading and storage. To keep things neat, I used Pillow to resize images to a consistent 1:1 ratio with a white background.

**Sharing on Social**
Sharing is caring, right? I aimed to share deals on Twitter too, but for now, I focused on Telegram. I sent messages through URLs to a dedicated Telegram channel. A Telegram bot, thanks to Bot Father, helped me achieve this.

**The Big Finish**
After putting my creativity and problem-solving skills to the test, Deal Forum Bot came to life. It uncovers fantastic deals and effortlessly shares them in a Telegram channel. And yes, I've added affiliate links to open doors to potential earnings through e-commerce affiliations. The final touch? Captivating images, catchy titles, prices, ratings, and insightful price history—all in one message.

For any questions or details, you can reach out to me at **prasanthrkkp2001@gmail.com.**

Feel free to make any further adjustments as needed. The aim here is to make it easy for anyone to understand and appreciate your project.
