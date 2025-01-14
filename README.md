# myRSSHub
RSSHub resources

## Deployment

RSSHub provides a painless deployment process if you are equipped with basic programming knowledge, you may open an issue if you believe you have encountered a problem not listed here, the community will try to sort it out asap.

## Docker Compose Deployment (Recommended)
### Install

Download docker-compose.yml
```
wget https://raw.githubusercontent.com/DIYgod/RSSHub/master/docker-compose.yml
```

Check if any configuration needs to be changed
```
vi docker-compose.yml  # or your favorite editor
```

Launch
```
docker-compose up -d
```
Open http://{Server IP}:1200 in your browser, enjoy it! ✅
My example:
```
http://www.felixshops.top:1200/cmpxchg8b/articles
http://www.felixshops.top:1200/google/research
```
Docs: https://docs.rsshub.app/guide/

### Update
**Automatic Update**

Use watchtower

**Manual Update**

Update image
```
docker-compose pull
```
Restart container
```
docker-compose up -d
```
### Configuration

Edit environment in docker-compose.yml







