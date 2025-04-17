# WebScraping---HW3

# Which Scraper was selected and why?

Between the two options (Scrapy and Beautiful Soup), Beautiful Soup was chosen for this assignment. I personally have more experience with Beautiful Soup, so I found it easier and more intuitive to use compared to Scrapy. The syntax of BS4 is also simpler to understand, which made it a more practical choice for this project.


# Review of the Prompts and Short Disucssion of the Strategy in building the prompts 

This was definitely the most challenging part of the assignment for several reasons, which I’ll discuss later. The LLaMA model required extremely specific instructions to return the expected format. During testing, the responses often didn’t align with the desired output, so I had to explicitly guide the model—explaining both the expected structure of the output and the specific fields I wanted extracted.

Additionally, I had to clarify how to handle missing data: what default values to use when certain fields weren’t found. Although these cases were documented in the assignment and addressed in the Beautiful Soup code, some rows lacked sufficient data yet still contained important information, which added complexity to the scraping process.

# Summary of Python Development Tools 

All of this was done with Python 3.13.3 on Visual Studio Code. 

# Summary of the Plan for Developing the functions and review of any diffuclties or hurdles in completing the code 

My initial plan was to first complete the Beautiful Soup scraper, and then tackle the AI scraper portion, which I anticipated would be the more difficult task.

One major difficulty was dealing with rows that included multiple sub-rows. This structure caused several issues in the Beautiful Soup implementation, but I eventually resolved them and got the scraper to parse the page correctly.

Another major hurdle was related to system limitations. My PC only has 8 GB of RAM, which made running the LLaMA model problematic—attempting to do so would crash the system. This unfortunate limitation impacted the quality and completeness of the AI scraper portion, but I worked within those constraints to deliver the best result possible.




