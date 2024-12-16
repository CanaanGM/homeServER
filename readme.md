# My Homeserver Applications 

> each service is in it's own file cause:
1. i like it this way
2. it's easier to manage/backup specific container
3. it's easier to make changes per container

- `.env` has no secrets that need to be emitted from git
- dashboard `.env` has API keys for some services, get these from the relevent service
  - eg: `HOMEPAGE_VAR_JELLYFIN_API_KEY=?????????`

## Getting started

- [install](https://docs.docker.com/engine/install/ubuntu/) docker
- allow ports on the firewall `sudo ufw allow [PORT]/tcp`
- adjust the PORTS and RAM in `.env` file of the service u wanna run
- get your user and group info and replace them for `PUID` & `PGID`
- run `docker compose up -d ` inside the service u want
- get the HDDS you have, mount them onto folders and replace the paths in the relevant `docker-compose.yml`


### Services

#### HomePage

> the dashboard for the server, i'm still testing it out

#### Komga
> [config page](https://komga.org/docs/installation/configuration/)

- manga and comics

#### AudioBookShelf

- [site](https://www.audiobookshelf.org/docs/#env-configuration)

for books and audiobooks

> to be managed by [Calibre](https://calibre-ebook.com/) on windows, then sent to the relevent db folder

#### JellyFin

- [site](https://jellyfin.org/)


- for shows, youtube rips, Movies and Anime

---

