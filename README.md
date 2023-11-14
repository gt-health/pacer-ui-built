# pacer-ui-built
 PACER UI with compiled code that can be deployed to http server.

## How to install
1. First, make sure your web server is running on the host machine that you will be running the pacer-ui.
2. Set up the server and find out where the web server folder is located.
3. From the repo (https://github.com/gt-health/pacer-ui-built), go to releases section and download "zip version".
4. Unzip the file and copy the contents of "pacer-ui" to web server's folder in your web server.
5. From the web server folder, go to assets\config\ folder.
6. Edit config.json. Put correct API URL in the file and save.

```
{
  "version": "",
  "title": "Pacer Client",
  "api": "http://<put your ECR manager URL>:8085"
}
```
7. Open browser and go to host URL.
