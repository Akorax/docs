# Troubleshooting
> This page is a stub and need to be filled with experiences from the community.
## Common Errors
> After a change in the database you will have to restart your server for the changes to take effect.

**1:** My server suddenly drop connection!\
**A:** If you have a remote or LAN-configured server. Have you checked so that the server computer isn't locked (ie. screensaver activated).

**2:** I'm stuck at `logging in to game server`!\
**A:** Is it your first log in? Your client will take some time to build the world database cache. Keep calm and grab a snack while you wait.

**3:** I'm stuck at `connecting`!\
**A:** In your `database`, double check your `realmd` table settings. Have you added the IP-address or DNS-server name correctly.

**4:** I can connect to my server but my friends can't!\
**A1:** Check your server [configuration](https://akorax.github.io/docs/#/_pages/Setup3).\
**A2:** Check your router/firewall settings. Certain ports must be forwarded.\
**A3:** Could be multiple reasons, come to discord with a detailed description of the issue if you still haven't resolved it.  

**5:** I get sent back to realmlist when I select a realm to play on.\
**A:** In your `database`, double check your `realmd` table settings. Try using your LAN IP-address instead of `127.0.0.1`.

**6:** Webserver website return internal server error 500 (Windows)\
**A:** Possible file path conflict related to MS OneDrive. Try moving your server folder C:\games for example. 

## Error Messages
Below is a list of WoW-errors. So far, I've only encountered the connection error.

| Error         | Description    | Solution |
|---------------|------------|-------------|
| BLZ51903003 | Network issue    | Try resetting your internet connection  |
| WOW51900314 | Connection Error | If you're using Classic client, double check that IP-address in hermesproxy.config is correct.  |
| WOW51900118 | World server not available | Check server avaibility, possible maintenance time  |
| WOW51900309 | Realm server issue | Try restarting your client  |
| WOW51900319 | Connection reset by peer | Try disabling Microsoft Defender Network Extensions or check for any security program or function that might interfere with neworking or your WoW-client. (Some Mac-users have had to update their OS) |
| WoW Error 132 | Client crash   | Check that your addons and graphic drivers are up to date |

 ## Error Reporting
> Discord is the main support channel right now.
### Discord
When asking for help on the SPP Discord server, try to describe your issue in detail with enough context.
```
Issue: I can't connect to my server
Description: I get thrown back to the realm selection list when I try to join a realm.
Context: I'm running the server on my computer/local machine and I'm using the vanilla client (1.12).
```
