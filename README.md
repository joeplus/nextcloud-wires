# Nextcloud integration with the [ifttt webhooks applet](https://ifttt.com/maker_webhooks)
Since ifttt.com changed their maker channel to a more general webhooks applet it is quite easy to send and receive requests from your nextcloud instance.

## Purpose
ifttt has many possibilities to connect different services based on triggers and actions. You could for example download all you Instagram pictures to a specific folder in nextcloud or add a task based on an email you receive.

## Goal
nextcloud-ifttt will provide external APIs for different actions which can be triggered by the ifttt webhook applet. The APIs will reuse internal nextcloud routes. Additionally the app will encapsulate all required configurations in the users personal settings menu.
