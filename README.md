[View Live Site](https://phakmovies.cf)
[Go To Movies Dir](https://github.com/nikhilpatidar/phakmovies/tree/master/content/movies)

## How to add a new movie

Create a _movie-name.md_ file in __content > movies__ directory.

Inside _movie-name.md_ file add the movie info on the top in the following format:
```
---
title: Movie Name
date: 2021-09-09
author: Author Name
---
```
- `date` should be in YYYY-MM-DD format
- `author` is optional

## Adding youtube video
Inside _movie-name.md_ you can add youtube videos with this shortcode:
```
{{< youtube <video-id-here> >}}
```

- Example(`https://youtu.be/aqz-KE-bpKQ`)
```
{{< youtube aqz-KE-bpKQ >}}
```

## Adding download button
You can add the download button like:
```
{{< download "full-download-link-here" >}}
```

## Adding telegram join button
Add a telegram channel join button:
```
{{< telegram "channel-name-here" >}}
```
Dont add `@` before channel name
