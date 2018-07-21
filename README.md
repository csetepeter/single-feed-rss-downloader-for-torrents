# single-feed-rss-downloader-for-torrents
Does what it says (hopefully)

you have to paste your correct folders with complete path at the end of the file (scroll down, it's kind of long, you'll see which parts you'll have to edit)

once done, run it in cron or manually, my cron job is the following (without apostrophes):
'* * * * *    php /root/rsstotorrent/rss.php'
which translates to run every minute. i use deluge on an armbian os (opi zero), the autoadd plugin automatically removes added .torrent files so the .torrent files do NOT get removed by this php file as far as i know.
