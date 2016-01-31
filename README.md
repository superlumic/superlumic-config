# superlumic-config

This is the default configuration "role" for [Superlumic](https://github.com/superlumic/superlumic). You will want
to fork this one and alter "default.yml". Alternatively, you can create additional YAML files to suit specific needs. Use the roles
folder to create "profiles".

How you organise your config files is entirely up to you, but this is
how I do it. The "profile-all" role are the apps and settings that
everyone in my company needs. Then I have a group file per type of
installation (developers, designers, etc). In specific "username.yml"
playbooks I then add all the specific things for the corresponding users (with "default.yml" being a reference for what a default user might want).
