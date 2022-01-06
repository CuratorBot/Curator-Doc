# Cloned VCs

## Overview

Normal VCs is your basic Custom VC creation that can be customized the channel owner without restrictions.

### Behavior

Cloned VC's behavior is simple, Users join the **`🔊｜Join to Clone`** VC and Curator in turn creates a Voice Channel and Text Channel identical to the settings set in the Parent Voice Channel. Channel owners can still change some it's settings but it's very limited.

### Creation

Creating a Cloned VC is simple:

1. Simply type **`/setup clone`** and Curator would create a Category named **`Clone Channels`** and a Voice Channel named **`🔊｜Join to Clone`** inside.
2. You can then rename the Voice channel to whatever you want e.g. (Duo, Trio, Party), You can also specify a user count for that corresponding Voice Channel.

{% hint style="info" %}
**NOTE:** That after running the /setup clone command, the created category is automatically selected
{% endhint %}

### Adding Cloned Channels

You can manage Cloned Channels by using the **`/clone`** command. To add a cloned channel, follow these simple steps:

1. Type **`/clone select #cloneChannelCategory`** to select the category you wish to manage.
2. Once, selected, you can type **`/clone add [channel name]`** to add more cloned VCs. You can optionally add a **channel name** upon creation of the channel. The channel name defaults to **`New Clone Channel`**.

### Removing Cloned Channels

As mentioned above, you can manage Clone Channels by using the **`/clone`** command. To remove a cloned channel, follow these simple steps:

1. Type **`/clone select #cloneChannelCategory`** to select the category you wish to manage.
2. Once, selected, you can type **`/clone remove #cloneChannel`** to remove the selected cloned VC.
