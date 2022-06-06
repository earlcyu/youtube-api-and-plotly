# Analyzing Urban Planning YT Channels: A Data Science Project Using YouTube API and Plotly
By: Earl Christian Yu <br/>
Date: June 5, 2022 <br/>
<br/>
## Overview
Inspired by Thu Vu data analytics's YT video on YT APIs, I decided to try out YT's API for myself to practice my data gathering, cleaning, and visualizing skills. Recently, I've been quite interested in urban planning, so I will analyze some urban planning youtubers for this project.
## Technical Learnings
Besides the actual mechanism of using a YT API, here are some technical things I learned along the way:
1. Convert YouTube time to datetime by using parser.parse. The output above will contain a timezone. Remove that by using x.replace(tzinfo=None).
2. Convert YouTube duration by using isodate.parse_duration(x).
3. Use try/except when there's a chance that applying a function will result to an error. Try/except is eseentially the Python equivalent of Excel's =IFERROR() function.
