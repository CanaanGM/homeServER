# My Homeserver Applications 

> each service is in it's own file cause:
1. i like it this way
2. it's easier to manage/backup specific container
3. it's easier to make changes per container

- `.env` has no secrets that need to be emitted from git
- dashboard `.env` has API keys for some services, get these from the relevent service
  - eg: `HOMEPAGE_VAR_JELLYFIN_API_KEY=?????????`


## Komga
> [config page](https://komga.org/docs/installation/configuration/)


## AudioBookShelf

- [site](https://www.audiobookshelf.org/docs/#env-configuration)

for books and audiobooks

> to be managed by [Calibre](https://calibre-ebook.com/) on windows, then sent to the relevent db folder

## JellyFin

- [site](https://jellyfin.org/)