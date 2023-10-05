# PostStatus - v1.0
Posts the Empire News and Power reports to Discord

Add the dependancies:
cpan -i WebService::Discord::Webhook
cpan -i File::Slurp

Add your webhook at:
/root/.MyHook.txt

Add to crontab:
1 0 * * * /root/PostStatus/poststats

