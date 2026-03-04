 # RosterHelper discord bot
 
 This bot uses the RaidHelper APIs to compare two events, helping to identify players who:

 - Signed to both the current raid and the previous raid, but did not get a spot in the previous raid
 - Signed to the current raid but did not sign to the previous raid

This is to help the raid leaders identify players who may have been overlooked in the previous raid, or who may not be
able to participate on raids on certain days
 
 ## Installation
 
 - Clone the repository, install with `npm install`
 
 - Copy the `config.example.json`, and rename to `config.json` - fill out the necessary fields
 
 - If this is for a new server, or commands in the bot have changed, you may need to run `npm run deploy-changes` to register slash commands into the server
 
 - Run the server with `npm run start-bot`
 
 - The `/findbenched` command should now function while this is running
 
 - If deploying to a server for permanant usage, install as a service
 
 