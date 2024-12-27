Who & When: Jess Lark, 2024

Project:
Mario Bar Chart - shows the number of Mario games by year released, that are available to play on Switch. A notable miss is Super Mario Sunshine. :(

Why:
Learning D3. It's been a while since I built a chart in D3.

How to Use:
This should work out of the box, locally or on a server. Just open the HTML file.

Notes:
I was working locally so I grabbed the data from RAWG and copied it in as a constant. 
- Upsides: no CORS worries, no lag, no secret key concerns
- Downsides: if the data is wrong is a pain to fix, the search might not be perfect and changing it is a pain, if new games are released we won't see them, etc

This is a first draft and is missing several elements of a good chart, such as axes. The design is also purely for ease of working and isn't particularly good. However, I wanted to version as things are working, so here is the MVP. (Most Valuable Project: the one you complete enough of to share).