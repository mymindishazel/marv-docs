# The load balancing issues

To understand this, you first need to understand what an immense amount of requests Marv handles. Thousands or even millions of requests - every day.

Because of this immense amount, Marv couldn't be run on one physical server alone anymore. It needed two.

### Here is where the issue arises:

Marv splits the discord servers between two physical servers, but only one physical server has ["marv.land", aka the support-server](https://discord.gg/WmDyx7C).
But only on that server, the premium-role is assigned by the Patreon integration.

### Meaning, the physical server which doesn't include the support server, can't check the premium role.

Hence, about 50% of the total servers have issues with premium.

### Luckily, there is a fix!

That's where Marv Patreon comes in. Marv Patreon, also nicknamed "Parv", only needs to run on one physical server, due to it only being for Patreon Supporters.
Which also means: **no load balancing issues there, wooohooooo**.
If you are a $4+ Donator, aka have premium, you're also able to invite Marv Patreon.
Just use [this link](https://discordapp.com/oauth2/authorize?scope=bot&client_id=368424172730187786&permissions=37080128), do the same steps you did with Marv aaaaand you're done. Premium you have.

## "I'm still angory about it!!!"

Luckily, this issue will be solved in the next version of Marv, which is already being coded!
If you want to help speed up development, feel free to become a tester!
Just do `=rank testers`, reply with `1` and you're done. You'll get access to our exclusive testers-lounge.
If you find any bugs with the test-version of Marv 3.0, Marv "Canary", "Qanary", "Cannary" or whatever we currently nicknamed it, feel free to send them directly into #testers!
Thanks for helping out c:
