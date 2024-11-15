# Get the process listening on a given port

```sh
sudo lsof -i -P | grep LISTEN | grep :$PORT
```
