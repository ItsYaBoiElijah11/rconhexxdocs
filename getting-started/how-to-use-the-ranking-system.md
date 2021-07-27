# How to use the ranking system





## Getting Started Using Rcon Hexx Tickets!

Now that you either changed the server prefix or kept it the same. you can now participate in the next step. using Hexx Tickets

```markup
First you will need a channel for the rank up messages to go!
```

{% hint style="info" %}
 Note: if you ever delete the category by accident you can redo the setup process witch only takes 5-10 seconds!
{% endhint %}

How to start setup:

```markup
<prefix>setrank <#rank_up_channel>
```

this is a little different from the ticket setup because this one you send the channel not the category id!



How to set a custom rank up message:

```markup
<prefix>setrankmsg <message>
```

Example: hexxsetrankmsg congrats {user.tag} at the new rank! new rank: {level} exp: {exp}



The message variables allowed for this:

```markup
You can also use this variables:

{user.tag} = Example#0001
{user.mention} = @Example#0001
{level} = 1
{exp} = 25

```



How to check the ranking leaderboard for that server!

```markup
<prefix>rlb
```

{% hint style="warning" %}
Note: this does not work if you try to spam messages and if the rank system is not setup yet
{% endhint %}

How to check your rank in a server:

```markup
<prefix>rank
```

And that's it for the ranking system!

{% hint style="info" %}
Next to be added: rank backgrounds, a few bug fixes, and something special.
{% endhint %}

The list of things to get started:

1. How to use custom prefix's \| **Completed**
2. How to use the ticket system \| **Completed** 
3. How to use ranking system \| **Incomplete**

