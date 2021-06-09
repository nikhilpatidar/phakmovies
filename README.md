[View Live Site](https://thetechnohack.cf)

## How to add a new movie

Create a <movie-name>.md file in __content > movies__ directory.

Inside <movie-name>.md file add the movie info on the top in the following format:
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
Inside <movie-name>.md you can add youtube videoes with this shortcode:
```
{{< youtube <video-id-here> >}}
```

- Example(https://youtu.be/aqz-KE-bpKQ)
```
{{< youtube aqz-KE-bpKQ >}}
```

## Adding download button
You can add the download button like:
```
{{< download "full-link-here" >}}
```

## Adding telegram join button
Add a telegram channel join button:
```
{{< telegram "channel-name-here" >}}
```
Dont add `@` before channel name

