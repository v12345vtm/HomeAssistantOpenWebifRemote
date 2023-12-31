
1) Hosting files

If you want to use Home Assistant to host or serve static files then create a directory called www under the configuration path (/config). The static files in www/ can be accessed by the following URL http://your.domain:8123/local/, for example audio.mp3 would be accessed as http://your.domain:8123/local/audio.mp3.
If you’ve had to create the www/ folder for the first time, you’ll need to restart Home Assistant.
Files served from the www folder (/local/ URL), aren’t protected by the Home Assistant authentication. Files stored in this folder, if the URL is known, can be accessed by anybody without authentication.
https://www.home-assistant.io/integrations/http/#hosting-files

2) copy tvv.html and dreammotelang.png to /www folder
3) edit the ip in de html code to your sat decoder ip

4) add a webpage card ( according image homeAssitant config card .png)

5) info : https://community.home-assistant.io/t/a-simple-remote-control-to-sat-recievers-openwebif-openpli/664094


