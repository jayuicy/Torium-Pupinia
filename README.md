# Pupinia Overview

This is the official page for Torium Pupinia bot.


## What is this?
Pupinia is a Discord Bot, designed to assist staff with their holy duties. This bot should be added to a private discord server, with no other members, where it can be used.

## Verification/Setup
1. [Invite Torium Pupinia](https://discord.com/oauth2/authorize?client_id=1335940063321653290) to your server.
2. Run !verify (RBLXUsername)
3. Follow the steps given.
4. Once verification is successful, the commands will register. Explore these yourself.
Only DS Staff will have access to the bot.

## Security Features
- Verification system, ensures only staff can use the bot.
- Checks your rank everytime a command is sent.
- Leaves the guild if you are demoted/an unverified person tries to use the bot.
- Ephemeral responses to prevent leaking.

## Command List

<details>
<summary>Expand Command List</summary>

If any of the commands listed here are not visible for you, run the !refresh command and try again.

- /getserver (lbe/dpi)
  - Displayers LBE's/DPI's server list and gives join command to specific worlds/wards.
- /getdoc (option)
  - Get the message link to any DS document + link to document. Options: Emerald, Moderation, In-Game Moderation, DPI Dress Code, Nurse Regulations, LBE Dress Code, Lunar Regulations, Trinity, Divine Sister All Docs
- /getformat (option)
  - Get the message link any DS message format. Options: Exploit, Bug, Inactivity Notice
- /getlink (option)
  - Get the link of any DS link. Options: Divine Sister Group, The Ranking Center, De Pride Isle, Les Beyond East, Gaymoria, Update Button, Holy Support, Nun Hat, Appeals Court
- /ssstatus
  - Displays if sunday service is active/inactive, and the time remaining.
- /logstars (week) (hours) (total) (stars) (startotal)
  - Logs your stars for the week  in a selected channel. 
- /logeval (week) (hours) (total) (evaluation result)
  - Logs your stars for the week in a selected channel.
- /logstarremoval (week) (starssremoved) (totalstars) (penalty)
  - Logs your warnings/strikes/star removals.
- /whois (username)
   - Retrieves information about the inputted user.

  For the reform log commands, these are designed to be used alongside the RoPro extension, where (week) is the week of your staff journey, (hours) is your weekly hours, (total) is your total hours, (stars) is your stars you received that week, (startotal) is the total amount of stars you currently have.
 </details>


## Notices
This bot has no affiliation with Divine Sister, or the HR/Developer team. All issues to do with this bot should be forwarded to my Discord account: jayuicy

## Update Log

<details>
  <summary>Expand Update Log</summary>

  ### Version 1.3.0 (31st May 2025)
- Added new /whois command.
   - Usage: /whois (username)
   - Displays target user's Username, ROBLOX ID, Rank in DS, Account Age, Avatar, Eligibility for Divinor and Profile Link.
- Fixed star and startotal being mixed up with the /logstars command.

  ### Version 1.2.2 (14th May 2025)
- Fixed crash bug when utilising the console button for the /getserver command.

  ### Version 1.2.1 (9th February 2025)
- Fixed bug displaying incorrect role emoji for the reform-logging commands.
   - Now displays the correct servant moon instead of stootiate moon for Maha Servants

### Version 1.2.0 (8th February 2025)
- Updated /getlink command
  - Added 'Appeals Court' option
- Update /getdoc command
   - Added 'LBE Dress Code' and 'Lunar Regulations'
- Added new !refresh command
   - Run this command to re-register slash commands for updates.

### Version 1.1.1 (8th February 2025)
- Made minor adjustments to /ssstatus command
   - Ensured proper time remaining is displayed, will need to wait until Sunday Service is inactive to see if these adjustments are properly functioning.

### Version 1.1.0 (4th February 2025)
- Removed option to get the LBE Recipes document from the /getdoc command due to the document being deleted.
   - Fixed crashing when executing the command.

</details>
