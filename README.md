# PostStatus - v1.2
Posts the Empire News and Power reports to Discord

[![Download PostStatus For Wolfpack Empire](https://img.shields.io/sourceforge/dm/poststatus.svg)](https://sourceforge.net/projects/poststatus/files/latest/download)

[![Download PostStatus For Wolfpack Empire](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/poststatus/files/latest/download)


Add the dependancies:

    cpan -i WebService::Discord::Webhook
    cpan -i File::Slurp

Create your webhook here:

![WebHook_Setup2](https://empiredirectory.net/WebHook_Setup2.png)

Paste your webhook into:

/root/.MyHook.txt

Add to crontab:

    1 0 * * * /root/PostStatus/poststats

