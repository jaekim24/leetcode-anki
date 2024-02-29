# Leetcode Anki
I wanted to leetcode on the go. Anki does have an app but cost money. You can still use the web browser version for free on your phone. You can sync decks which is really easy with an account. 

Anki takes advantage of two studying techqiues spaced repetition and active recall.

# Video to make your own leetcode anki
Here is a great video basically teaching you how to kind of use anki. It teaches you how to make decks and customize the cards and such. [link](https://www.youtube.com/watch?v=WInP22evPJE)

# Code Syntax Highlighting add-on
- [link](https://ankiweb.net/shared/info/566351439)
1. Download code ``` 566351439 ```
2. For those who don't know, you can use this in dark mode by changing the style to e.g. monokai

	1.Tools → Add-ons → Syntax Highlighting (NG) → Config

		```
		{
		    "hotkey": "Alt+s",
		    "limitToLangs": [],
		    "style": "monokai"
		}
		```

# Using anki
You can create or import a deck 

![Screenshot 2024-02-27 193046](https://github.com/jaekim24/leetcode-anki/assets/62858192/ff985657-c993-4670-8e07-521b87a44271)

This is what the front looks like

![Screenshot 2024-02-27 193125](https://github.com/jaekim24/leetcode-anki/assets/62858192/892ba494-c49a-42f9-9c4c-44cc90e24d75)

You can click show answer or press the space bar

![Screenshot 2024-02-27 193225](https://github.com/jaekim24/leetcode-anki/assets/62858192/5391ff49-d9e7-41e9-bb53-cae4f4b92d7b)

# New spaced repetition algorithm: FSRS [link](https://github.com/open-spaced-repetition/fsrs4anki/wiki/Spaced-Repetition-Algorithm:-A-Three%E2%80%90Day-Journey-from-Novice-to-Expert)
Free Spaced Repetition Scheduler
More info [link](https://medium.com/@JarrettYe/how-did-i-publish-a-paper-in-acmkdd-as-an-undergraduate-c0199baddf31)

How to enable FSRS [link](https://github.com/open-spaced-repetition/fsrs4anki/blob/main/docs/tutorial.md)

# Another flashcard format ( I am going to give it a try )  [link](https://news.ycombinator.com/item?id=35517232)
This is rsaneks flashcard format.
This note type is stored under rsaneks_question_card_format. Copy and pasted from rsaneks post.

For my job search process I created a custom note type specifically for interview problems. My general process was go to LeetCode, find a medium/hard problem, hack on it for 30-60 minutes, then look at the solution if I couldn't get there myself. At the end of the problem, regardless of if I solved it or not, I'd create an Anki card with the following fields:
Title

Question

Additional Criteria

Example input/output

Insight (1 sentence maximum)

Insight explanation (can be longer/bullet-pointed list)

Key Data Structure (at most 1 data structure; if there are multiple, use the most important one)

Time complexity

Space complexity

Full answer code (can use syntax highlighter add-on)

Source (can provide link to associated question online; can include link(s) to solutions that the insight and/or code come from)

There are 4 cards that are generated from this template, which test the same question in slightly different ways. They individually ask for the insight, the key data structure, and the time and space complexities.

I found this note type to be critical to my success in the following interviews. In two cases, I was asked literally the same exact question I had already added to Anki; I was able to write out the solution from memory in one go. If you'd like to use my note type directly, I've exported an example here. [0




