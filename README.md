# PostStatus - v1.0
Posts the Empire News and Power reports to Discord

Add the dependancies:

    cpan -i WebService::Discord::Webhook
    cpan -i File::Slurp

Create your webhook here:

![WebHook_Setup2](WebHook_Setup2.png)

Paste your webhook into:

/root/.MyHook.txt

Add to crontab:

    1 0 * * * /root/PostStatus/poststats

