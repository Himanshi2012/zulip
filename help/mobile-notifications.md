# Mobile notifications

You can customize whether [stream messages](/help/stream-notifications),
[direct messages](/help/dm-mention-alert-notifications) and
[mentions][notifications-wildcard-mentions] trigger notifications in Zulip's
[Android](https://zulip.com/apps/ios) and [iOS](https://zulip.com/apps/ios)
apps.

{start_tabs}

{tab|desktop-web}

{settings_tab|notifications}

1. Toggle the checkboxes for **Streams** and **DMs, mentions, and alerts**
   in the **Mobile** column of the **Notification triggers** table.

{end_tabs}

[notifications-wildcard-mentions]: /help/dm-mention-alert-notifications#wildcard-mentions

## Mobile notifications while online

You can customize whether or not Zulip will send mobile push
notifications while you are actively using one of the Zulip apps.

!!! tip ""
    When testing mobile notifications, make sure Zulip is
    configured to send mobile notifications even when you're online.

{start_tabs}

{tab|desktop-web}

{settings_tab|notifications}

1. Under **Mobile message notifications**, toggle
   **Send mobile notifications even if I'm online**, as desired.

{end_tabs}

## Troubleshooting mobile notifications

### Checking your device settings

Some Android vendors have added extra device-level settings that can impact the
delivery of mobile notifications to apps like Zulip. If you're having issues
with Zulip notifications on your Android phone, we recommend Signal's excellent
[troubleshooting guide](https://support.signal.org/hc/en-us/articles/360007318711-Troubleshooting-Notifications#android_notifications_troubleshooting),
which explains the notification settings for many popular Android vendors.

### Enabling push notifications for self-hosted servers

!!! warn ""

    These instructions do not apply to Zulip Cloud organizations (`*.zulipchat.com`).

To enable push notifications for your organization, your server administrator
will need to register your Zulip server with the [Zulip mobile push notification
service](https://zulip.readthedocs.io/en/stable/production/mobile-push-notifications.html).

#### Check whether notifications have been set up on your Zulip server

{start_tabs}

{tab|mobile}

{!mobile-profile-menu.md!}

1. Tap **Settings**.

1. Tap **Notifications**. If notifications have not been set up, you will see a
   banner that indicates this.

{end_tabs}

### Contacting Zulip support

If you are still having trouble with your push notifications, you can send an
email to [Zulip support](/help/contact-support). Please be sure to include the
troubleshooting data provided by the mobile app.

{start_tabs}

{tab|mobile}

{!mobile-profile-menu.md!}

1. Tap **Settings**.

1. Tap **Notifications**.

1. Tap **Troubleshooting**.

1. Use the **Copy to clipboard** button or the **Email support@zulip.com**
   button to email the troubleshooting data to the Zulip support team.

{end_tabs}

## Related articles

* [Stream notifications](/help/stream-notifications)
* [DMs, mentions, and alerts](/help/dm-mention-alert-notifications)
* [Email notifications](/help/email-notifications)
* [Desktop notifications](/help/desktop-notifications)
* [Do not disturb](/help/do-not-disturb)
