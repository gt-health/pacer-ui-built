# pacer-ui-built
 PACER UI with compiled code that can be deployed to http server.

## How to install
1. First, make sure your web server is running on the host machine that you will be running the pacer-ui.
2. Set up the server and find out where the web server folder is located.
3. Download "zip version" the version you want from release section
4. Unzip the file and copy the contents of "pacer-ui" to webserver's folder in your web server.
5. From the pacer-ui folder, go to ..\assets\config\ folder.
6. Edit config.json. Put correct api URL in the file.

```
{
  "version": "",
  "title": "Pacer Client",
  "api": "http://<puy yout indysnvr nsmr:8085"
}
```
7. Open browser and go to host URL.
