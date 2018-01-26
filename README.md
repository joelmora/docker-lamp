# Docker-lamp

Simple lamp for local development environment


## Installation

```
$ docker-compose up -d
```

## DNS resolver and port forward with POW (optional)

1. Define TLD
```
$ nano ~/.powconfig
```

Fill it with: 
```
export POW_DOMAINS=test,local,[ANOTHER-TLD]
```

2. Install POW
```
$ sudo curl get.pow.cx | sh
```

More info on [http://pow.cx/manual.html](http://pow.cx/manual.html)

3. `.local` domains

For .local domains Open `System Preferences > Network > Advanced > DNS Tab` and add `.local` to `Search Domains`

4. 

