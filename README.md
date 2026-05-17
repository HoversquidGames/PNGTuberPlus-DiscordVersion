kaikairos's PNGTuber Plus program that uses Discord User Ids instead of mic activation to allow users in voice calls to activate the speaking sprite.

<img width="731" height="530" alt="image" src="https://github.com/user-attachments/assets/94a717c1-c775-445e-abbd-d28b3adaae46" />



How to use:

1. Go to the [Discord Development portal](https://discord.com/developers/home) and set up a new bot.
2. Give it the permissions for View Channels, Connect, and Use Voice Activity.
3. Connect it to your server(s).
4. Get the public key, client ID, token, and your server ID. Change the `.env.example` name to `.env`, and input these values into the respective fields.
5. Start the DiscordVoiceBot server, wait for: "[BOT] Slash commands registered." to show.
6. Join a Discord Voice call and use the slash command `/join`.
7. Start the PNGTuberPlusDiscordVersion app, and enter the user ID for the user that should control the model's speaking state with their voice state.
8. Start an app for each user.
