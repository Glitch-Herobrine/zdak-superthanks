# zdak-superthanks
**_almost_** All of Superthanks comments sent to the YouTuber zdak.
## Example Data
```json
  {
    "author": "@example",
    "amount": "$5,00",
    "content": "Thanks!",
    "likes": "123",
    "authorProfilePicture": null
  },
```
**Author:** The handle of the comment's author.

**Amount:** The amount of money sent with the currency at the beginning.

**Content:** The content of the comment.

**Likes:** The abbreviated amount of likes.

**authorProfilePicture:** The profile picture URL of the author. **Warning: This entry is sometimes null, due to the speed of the parsing. Do not depend on this parameter.**

## How is this data obtained?
Using Cheerio and Puppeteer in node.js, with an automated browser that goes through every video. Why? Youtube API does not return the amount of money donated on comments.

## Disclaimer:
This project is a fun, e ducational experiment meant to test webscraping capabilities.
It is not affiliated with or endorsed by YouTube or Zdak.
