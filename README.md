# User-info-command
Outputs an embed of the users status, activity, tag, ID, badges, account joined and created at.

You'll have to have a command handler or put

else if (command === "userinfo") {
    client.command.get("userinfo").run(client, message, args);
  }

In your index.js file/main file
