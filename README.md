# Vull

Vull is a bot mainly aimed at moderation. It has some other commands for info but that is really it.
Vull is meant to be minimal.

# Consider this.

If you change the logger to 0 in `src/configs/customConf.json` Vull **will** break. It requires MongoDB to function properly.

If you edit the version in `src/configs/customConf.json` Vull will then proceed to show innacurate versioning.

# Setting up your token

Create a `templateConf.json` file in the `src/configs` directory.
Edit the config file to look something like this:
```
{
    "bot": {
        "token": "You're token here"
    }
}
```
Replace `You're token here` with your bots token.

# Configs

Anything else in the config is yours to play around with.

# Youtube and gitlab commands

These commands are restricted by access tokens/keys from youtube or gitlab.
Get the keys and put them in src/configs/cTokenConf.json as

```json
{
  "ytToken": "youtubeTokenHere, optional",
  "glToken": "gitlab token here, optional.",
  "glURL": "URL of the gitlab instance here, optional"
}
```
(All are optional)

# Liability

I, Null#0515 (VoidNulll) take no responsibility for you're own actions, corrupted files, personal loss, or any sort of damages caused to you, you're company, or you're device. You are responsible for your actions on the internet and with what you run.

# Agreement

By using Vull, You agree to not modify, adapt, or change the Info command. You may also not modify, adapt, or change the acknowledgements part of the Who/Whois/Userinfo command. The usage nor the function nor where the function is used may be in any way altered, adapted, or changed for any reason.
This stands unless I agree to allow You to modify, adapt, alter, or change any of these.
This agreement stands in any and versions, names, forks, or usages of Vull
