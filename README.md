# colabtorrent
Download torrents using Colab
---
If you've come here then you're already aware of Google Colab. It is a tool for Machine Learning researchers to share their work. They provide a remote Jupyter notebook that runs on a linux environment with 12Gigs of RAM and ~300 Gigs of disk space. 

My college LAN has blacklisted downloads from torrents. So modern problems require modern solutions. Here's how to download torrents and transfer it to your google drive.

1) Get the torrent file and upload it to your colab runtime.

2) Mount your google drive to colab runtime.

3) As colab enables users to use linux commands in Jupyter notebooks just by placing '!' before any command.

4) Install transmission-cli using the command:

  ``` 
  !apt-get install transmission-cli
  ```
  or
  ```
  import os
  os.system('apt-get install transmission-cli')
  ```





NOTE: This is for educational purposes only. There is no intention to eploit free resources provided by COLAB.
