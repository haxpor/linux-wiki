# linux-wiki
Notes, references and things I learned and found interesting in Linux ecosystem

This is meant to be placed on web server as it is.

# Build
* `src` contains the source in `.txt` file before processing
* `posts` contains output `.html` files
* `footer.html` is footer in html format to be included in processing for every post
* `header.html` is header in html format to be included in processing for every post

Processing uses `pandoc` with following command

```
pandoc -B header.html -A footer.html src/input.txt posts/output.html
```

# License
Copyrights 2019, Wasin Thonkaew.
In case of reprinting, or to do anything with the article you're unsure of, please write me e-mail.
