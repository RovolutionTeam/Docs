# Rovolution	

![Discord Logo](https://i.ibb.co/kB9yTD1/Dark-Studio.png)
 - - -

## Why use Rovolution?
1. Rovolution is a simple easy to use roblox to discord integration tool, it lets moderators pick a role in a roblox group and assign it to a discord role, so anyone with the group role will receive the Discord Role.
2. Rovolution is linked with the RoVer database and has uses of its own so it has over 3 million verified members, chances are you community is already verified.
3. Our bot has a ping of about 20ms and a uptime of 99.996% making it incredibly reliable to use.
4. Rovolution has a incredibly active support team and Data Security team, check out the support server to make a Data Delection Request, a Security Related issues, bug or just General Support.
5. The bot is **100% Free**, we have no intention is make the bot paid and you have full access to every command, one day we may need to ask for donations to pay for server infrastructure but we believe every user should get the same experience. There is no role bind limits and never will be.
- - - -
:::warning
### Rovolution Permissions
Rovolution ask for quite a few permissions, for quite setup just leave on default however if you are paranoid about securing your servers here are the permissions the bot requires for basic functionality.
```
Manage Nicknames
View Channels
Send Messages
Read Message History
Use External Emojis (this one, only affects how the bot looks and it will function without this permission.)
Add Reaction
```
If you want to use it as a music bot (still in beta testing) you will need the following permissions.
```
Connect
Speak
Use Voice Activity
```
:::
- - -
## How to use Rovolution
Now you have heard how great Rovolution is how do you use it?
### Quick Installation
Quickly get Rovolution working as a server defender in your group.
1. Download the bot using the link above.
2. Next step give yourself the `Database Manager` Role so you can edit Rovolution Server Configs
3. Run `!verifyChannel #tagchannel` Make sure you take the channel corectly. You don't have to run this command, however people will be able to verify anywhere, and people won't get Auto Verified so we recommend running this command.
4. The bot will work now and Auto Verify will be on so anyone joining who has verified with Rovolution or RoVer will get the Role `Verified`.
5. You can setup the role `Verified` and change its perms so you need to verified role to talk, effectively making a server verification guard. You can change the role  `Verified` permissions and colours, just don't change the name (same for `Bot Bypass` and `Database Manager`.
6. To turn off Auto Verification please see the command list below (`!autoVerify`) 

### Customising the bot
Now the bot is working lets attach some roles to our group.
1. Make sure you have the role `Database Manager` as this will be required.
2. Run the bind command, example `!bind @tagrole GroupId RankId` for more on how to use the command see the list below, and if you have any problems make a support query in the support server.
3. Test out the bot but remmeber `!verify` and `!getroles` only work in the channel you set for verification earlier.

### **If the bot isn't replying check that it can view the channel you are messaging in and that it has permission to talk there!**
Please see below for full command list.
- - -
### Basic Commands
#### Verify Command:
```css
!verify 
!getroles
```
Both these commands will update nickname and change roles, of the person who sent the message. The bot will only respond if in the designated channel, endless the verify channel hasn't been specified then the command can be used anywhere. If you have the role `BotBypass` then you can't use the verify command or be updated by moderators, you can use this as a away to mute people and prevent them getting there roles back.
- - - 
#### Help Command:
```css
!help
```
Relays the bot command information.
- - - 
#### Status Command:
```css
!status
```

Shows stats about the bot.
- - -
#### Uptime Command:
```css
!uptime
```

Shows the uptime for the bot.
- - -
#### ChangeLog:
```css
!changelog
```

Shows the change log for the bot.
- - -
#### Version:
```css
!version
```
Show your bot shards current version (mostly for debugging with engineers).
- - -
### Administrator Commands
All these commands require `Database Manager` role to run.
#### Bind Command:
```css
!bind @tagrole Groupid rankid
```
Example Usage:
```css
!bind @Member 12 1-255
```
```css
!bind @Member 12 1
```
This command physically binds a Roblox group role to a Discord role, this command can either except a range or a single rank, make sure your Roblox Group roles all have different ranks or the bot won't work. 
- - - 
#### Remove Binds:
```css
!clearbinds
```
This is a irreversible action if you have made a mistake when binding, it will clear all binds. If you have lots of binds and don't want to lose them all then make a `#general-support` query in the support server.
- - -
#### Verify Channel:
```css
!verifyChannel #tagchannel
```
Example usage
```css
!verifyChannel #verify
```
You will need to make a channel or use a already existing channel make sure to correctly tag it. This will lock all `!verify` and `!getroles` commands to that channel and it will also send a welcome message and autorole them on join.
- - -
#### Verify Status:
```css
!verifystatus @taguser
```
Example Usage:
```css
!verifystatus @GeraldisNice
```
This will give moderators basic info on the user to help crack down on alts, make sure to correctly tag the user you wish to receive data on.
- - -
#### Update User:
Example usage
```css
!update @taguser
```
Example Usage:
```css
!update @GeraldisNice
```
Allows moderators to forcibly update a users, as if they have run the `!verify` or `!getroles` command. This can be run in any channel but make sure to tag the user.
- - -
#### Bulk Delete Messages:
Example usage
```css
!delete (number between 1-100)
```
Example Usage:
```css
!delete 20
```
Allows moderators to bulk delete spam messages especially in raids.
- - -
#### Auto Verification:
Example usage
```css
!autoverify
```
Toggles auto verification on join.
- - -
#### Welcome Dm:
Example usage
```css
!welcomedm (message)
```
Example
```css
!welcomedm Welcome to my amazing server.
```
Sends a direct message to a user on join.
- - -
#### Clear Welcome:
Example usage
```css
!clearwelcome
```
Removes the welcome message on join.
- - -
#### Welcome:
Example usage
```css
!welcome
```
Toggle the message in the server on a new member joining.
- - -
#### Welcome Message:
Example usage
```css
!welcomemessage (message)
```
Example
```css
!welcomemessage Welcome to my awesome server.
```
Change the default message in the `#verify` channel (the one you set up earlier).
- - -
#### Rolebinds:
Example usage
```css
!rolebinds
```
Display current Rolebinds information.
- - -

# Important Information
To make full use of the bot make sure to run the `!verifyChannel #channel` command to allow auto verification and welcoming on join.

**If you accidently kick the bot and decide to invite it back it will remember your previous role binds and settings**

:::info
## Remember to join the support server if you need any help. https://discord.gg/xXPuh7b
:::
::: danger
### Security and Data Retention Policy.

To report a Data Breach or security issue please head to the support server and make a report.

If for any reason you need to get your data deleted, head to the support server and submit a data deletion request and in Compliance with GDPR policies we will delete all you data within 72 hours. To delete server info (rolebinds) you need to be the server owner and make a data deletion request.

:::
