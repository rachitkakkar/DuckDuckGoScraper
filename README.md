# DuckDuckGoScraper
A simple python file to scrape DuckDuckGo Search Results using BeautifulSoup and Selenium.

# Requirements
Python 3.9.1, dependencies listed in requirements.txt

# Usage
The search function takes in a string as the query and returns a dictionary. Each value in the dictionary has a title, domain, and description.
This is the following result using the query of "hello":

```
[{'title': 'HELLO! - Daily royal, celebrity, fashion, beauty ...', 'domain': 'https://www.hellomagazine.com/', 'description': 'HELLO! brings you the latest celebrity & royal news from the UK & around the world, magazine exclusives, fashion, beauty, lifestyle news, celeb babies, weddings, pregnancies and more!'}, {'title': 'Hello | Definition of Hello by Merriam-Webster', 'domain': 'https://www.merriam-webster.com/dictionary/hello', 'description': 'Definition of hello : an expression or gesture of greeting —used interjectionally in greeting, in answering the telephone, or to express surprise hello there waved hello Synonyms & Antonyms Example Sentences Learn More about hello Synonyms & Antonyms for hello'}, {'title': 'Hello | Definition of Hello at Dictionary.com', 'domain': 'https://www.dictionary.com/browse/hello', 'description': "(used to express a greeting, answer a telephone, or attract attention.) (an exclamation of surprise, wonder, elation, etc.) (used derisively to question the comprehension, intelligence, or common sense of the person being addressed): You're gonna go out with him?"}, {'title': 'Hello - Wikipedia', 'domain': 'https://en.wikipedia.org/wiki/Hello', 'description': 'Hello is alternatively thought to come from the word hallo (1840) via hollo (also holla, holloa, halloo, halloa). The definition of hollo is to shout or an exclamation originally shouted in a hunt when the quarry was spotted:. If I fly, Marcius,/Halloo me like a hare. — Coriolanus (I.viii.7), William Shakespeare'}, {'title': 'HELLO! US Edition - Latest news and Photos', 'domain': 'https://us.hellomagazine.com/', 'description': 'HELLO! US edition brings you the latest celebrity & royal news from the US & around the world, magazine exclusives, celeb babies, weddings, pregnancies and more'}, {'title': 'Hello Synonyms, Hello Antonyms | Thesaurus.com', 'domain': 'https://www.thesaurus.com/browse/hello', 'description': "Another word for hello. Find more ways to say hello, along with related words, antonyms and example phrases at Thesaurus.com, the world's most trusted free thesaurus."}, {'title': 'Hello! | Super Simple Songs - YouTube', 'domain': 'https://www.youtube.com/watch?v=tVlcKp3bWH8', 'description': 'More great Super Simple videos in the Super Simple App for iOS http://apple.co/2nW5hPdStart off your lesson with "Hello!", a fun and energetic song to talk...'}, {'title': 'Royal News - Latest Photos & Exclusives from The Royals ...', 'domain': 'https://www.hellomagazine.com/royalty/', 'description': 'Royal News: Get the latest from the royals here. Photos, features & live exclusives from royalty, european & round the world at HELLO! Magazine today'}, {'title': 'YouTube', 'domain': 'https://www.youtube.com/', 'description': 'Enjoy the videos and music you love, upload original content, and share it all with friends, family, and the world on YouTube.'}, {'title': 'hello network', 'domain': 'https://www.hello.com/en/index.html', 'description': 'hello has 1000s of communities! Create or join communities to connect around your specific interests. learn more. key features. personas & communities. Personas and user-created communities are focused on a particular passion. folio. Your folio is a personalized feed of content relevant to your chosen personas.'}]
```
# Blog
This is the code for the blog post: https://rachitkakkar.digitalpress.blog/scraping-duckduckgo-search-results-with-python-using-beatifulsoup-and-selenium/
