## 🕸️ Event Configuration: Set Up and Manage Server Rewards

HalloweenBot allows you to create fun, competitive events in your server where users can earn points by participating in a Trick-or-Treat style game. With the **/seteventconfig** command, you can configure the event settings, including the channel for event notifications and the role that will be awarded to the top users in your server.

### Setting Up Event Configuration

To set up and customize the event configuration for your server, follow these steps:

- **Choose a Channel and Set the Reward Role:**  
  Use the command `/seteventconfig config set` to begin the setup. First, select the channel where HalloweenBot will send event notifications. Next, choose the role that will be automatically awarded to the users with the highest amount of points in your server. This role will be granted based on users' event participation and point totals.

### Enabling or Disabling Event Messages

Once the event configuration is set up, you can control whether or not HalloweenBot sends event notifications.

- **Enable/Disable Event Messages:**  
  Use the command `/seteventconfig config` to toggle event messages on or off. When enabled, the bot will send an embedded message to the specified channel every 10-60 minutes. Server members must be quick and reply with the 🎃 emoji first in order to collect the reward points.

### Viewing Event Configuration

To check the current configuration of your server’s event settings, you can easily review them at any time.

- **View Event Configuration:**  
  Use the command `/seteventconfig view` to see the current settings, including the selected channel, the reward role, and whether the event messages are enabled or disabled.

### Leaderboard: Track Points

HalloweenBot also provides a leaderboard feature, allowing you to see who has accumulated the most points.

- **View Leaderboard:**  
  Use the command `/leaderboard scope server` to see the highest points in your server.  
  Use `/leaderboard scope global` to view the global leaderboard, showing the top players across all servers using HalloweenBot.

### Permissions Requirement

To ensure that the event configuration works correctly, HalloweenBot needs the **MANAGE ROLES** permission. This allows the bot to automatically assign the reward role to users based on their points.

By setting up and managing your event configurations, you can create an exciting and competitive atmosphere in your server, rewarding the most active participants and making Halloween even more fun!
