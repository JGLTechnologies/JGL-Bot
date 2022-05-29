<a href="https://jgltechnologies.com/discord">
<img src="https://discord.com/api/guilds/844418702430175272/embed.png">
</a>

# JGL Bot

Support for the bot can be given in the issues tab of the repository, at <a href="https://jgltechnologies.com/contact">https://jgltechnologies.com/contact</a>, or on our <a href="https://jgltechnologies.com/discord">Discord server</a>.

## Config

Setting a mute role:

`/set role name: Mute, role: @muted`
Leave role empty to unset it.

<br>

Valid role names:
  - Mute (Added when muted)
  - Mute Remove (Removed when muted)
  - Staff (Allows access to most admin commands)

<br>

Setting a logging channel:

`/set channel name: Logging, channel: #logging`
Leave channel empty to unset it.

<br>

Valid channel names:
  - Welcome (Welcome messages are sent here)
  - Goodbye (Goodbye messages are sent here)
  - Logging (Logs are sent here)

<br>

Setting a welcome message:

`/set message name: Welcome, message: {member} has joine the server!`
 Leave message empty to unset it.
 
<br>

Valid message names:
  - Welcome (Welcome message)
  - Goodbye (Goodbye message)

Setting a warning punishment:

`/set punishment punishment: Temp Ban, warning: 7, duration: Days, number: 5`
Leave punishment empty to unset it.
This will ban someone for 5 days when they get 7 warnings. Duration and number are not need when the punishment is not temporary.

<br>

Valid punishments:
  - Kick
  - Ban
  - Mute
  - Timeout
  - Temp Ban
  - Temp Mute

<br>

## Role Dependencies

A role dependecy is when a role is dependent on another role. So if one role gets removed so does the dependent role.

Creating a role dependency:

`/dependencies add role: @staff, dependent: @helper`
If @staff is removed, @helper will also be removed

Removing a role dependency:

`/dependencies remove role: @staff, dependent: @helper`






