### Introduction:
This Discord bot allows you to easily create and manage polls in your server. Users can vote by reacting to the options, and the bot will display the results in a graphical format.

### Commands:
1. **.start_poll**: Start a new poll in a specific channel. The bot will guide you through the setup process.

### How to Start a Poll:
1. Use the command `.start_poll` to initiate the poll creation process.
2. The bot will ask you to mention the channel where you want to start the poll.
3. Next, specify the channel where you want to send the poll result.
4. Provide options for the poll. You can add as many options as you like.
5. Assign emojis to each option to make it visually appealing.
6. Specify the duration of the poll in seconds.
7. The bot will create a poll message with options and emojis.

### Voting:
- Users can vote by reacting to the options with the assigned emojis.
- Each user can only vote once. If a user tries to vote again, the bot will remove their previous vote.

### Poll Result:
- After the specified duration, the bot will automatically tally the votes and display the results in an embedded message.
- The results include a graphical representation of the votes using a bar graph.
- The tally includes the number of votes for each option.

### Additional Information:
- The bot supports multi-option polls.
- You can customize the bot's prefix by modifying the `command_prefix` variable in the script.
- The bot utilizes the Discord.py library, PIL (Pillow) for image processing, and Matplotlib for creating graphs.

### Example Usage:
1. `.start_poll`
2. Mention the channel to start the poll.
3. Mention the channel to send the result.
4. Provide poll options (e.g., "Option 1", "Option 2").
5. Assign emojis to options.
6. Specify the poll duration (e.g., 60 seconds).
7. The bot creates the poll, and users can vote by reacting to options.
8. After the duration, the bot displays the poll result with a graphical representation.

Note - please have some common sense and altealst provide with 2 options to start polling.

### Important Notes:
- Ensure the bot has the necessary permissions (read messages, send messages, add reactions) in the channels where it operates.
