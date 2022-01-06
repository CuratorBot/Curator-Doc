# clone

#### Command Examples:

```fix
/clone select <#category OR categoryId>
/clone add [name]
/clone remove <#channel OR channelId>
```

#### Arguments

**`#category`** - The category you wish to select/remove.

**`categoryId`** - The ID of the channel you wish to select/remove.

**`name`** - An optional argument to set the name of the cloned channel it will create.

#### Description

The clone command is the main command manager for managing Cloned VCs. You use this command to manage existing Cloned VCs.

To use this command, you must first select the Cloned Channel you want to edit/manage. You can do this by running the **`/clone select <#category or categoryId>`** command.

{% hint style="warning" %}
**NOTE**: Make sure that you actually have Clone VCs available in your server. If not, kindly run the **`/setup clone`** command. After doing this command, the category is automatically selected.

You can also check if you have existing Clone VCs by running the **`/settings`** command.
{% endhint %}

Once you have the category selected, you can now use the **`/clone add`** command to add VCs. Simply run the **`/clone add`** command then Curator would make a new Voice Channel named **`New Clone Channel`**. You can optionally add an argument that would serve as the name of the VC created instead of the default.

You can also remove/delete Voice Channels by running the **`/clone remove`** command. To do this, simply run the **`/clone remove`** command and add either the **`channel`**, or the **`channelId`** of the channel you want to remove.
