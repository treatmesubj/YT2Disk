# YT2Disk

Uses HTTP requests, CSS selectors, and regular expressions to extract important information from a YouTube video's HTML & JS to present YouTube's available formats of the video, which the user can choose from to write its content to a local file very quickly. 

[youtube-dl](https://github.com/ytdl-org/youtube-dl) has many options, which is great if you need them, but it's thousands upon thousands of lines of code and supports various dubious sites. I figured I'd peruse through youtube-dl's source to learn how YouTube worked, but the code was so sprawling, I was having a hard time wrapping my head around it so, I set out to find out on my own and I started right with the YouTube video's webpage and worked my way from there in less than a hundred lines of clear and understandable code. 

![alt text](./attachments/scrot.png)
