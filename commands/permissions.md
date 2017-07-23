# Permissions

Marv allows you to restrict who can use Marv by two different approaches: whitelists and blacklists. 

<br>

### Whitelists

Whitelists are useful for large servers. Anyone who is on the whitelist will able to use Marv -- everyone else will get an error message.

- `-whitelist` Displays which users and roles are on the whitelist
- `-whitelist add @user/@role` Adds a user or role to the whitelist
- `-whitelist remove @user/@role` Removes a user or role from the whitelist

### Blacklists

Blacklists are useful for smaller servers. Everyone will be able to use Marv except for people on thie blacklist. This can help target problem users.

- `-blacklist` Displays which users and roles are on the blacklist
- `-blacklist add @user/@role` Adds a user or role to the blacklist
- `-blacklist remove @user/@role` Removes a user or role from the blacklist
