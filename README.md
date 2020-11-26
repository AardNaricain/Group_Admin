# Group_Admin
Automatically send group invites to people you designate.

# Syntax
autoinvite [on|off]: Toggle or set automation on/off, essentially enabling/disabling the plugin.

Autoinvite list: Display the list of people on your autoinvite list. These are the people to whom you will automatically send group invites upon login (assuming they're either in your clan or on your ftalk), who can send a tell asking for an invite, and who can utilize the gtell commands (see below).

Autoinvite list &lt;name&gt;: Add a person to your autoinvite list, or remove them if they are already present.

autoinvite msg [string]: Display or set your autoinvite message. This is what people tell or gtell to get invites from you. Default is simply 'invite', so by default, one need merely 'tell &lt;player&gt; invite'.

If you are on your group leader's autoinvite list, you can use gtell to have the leader automatically do a few things.

gtell invite &lt;person&gt;: Invites anyone. They do not need to be on leader's invite list.

gtell leader &lt;person&gt;: Make &lt;person&gt; the group leader.

gtell rename &lt;name&gt;: Rename the group to &lt;name&gt;.

gtell commands: Get a list of these available gtell commands.

Might add a gtell kick option in the future. Might also add some other admin-type things like aim counters, members in room/area, etc. when I feel less lazy...
