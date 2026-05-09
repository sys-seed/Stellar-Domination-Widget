# Stellar-Domination-Widget

Hi all !
Using the app Scriptable (free and open) you can generate widget on iOS.

Here the link for the app : https://apps.apple.com/fr/app/scriptable/id1405459188

I developed (Claude mostly did TBH, I did the fine tuning) a script to show a dashboard like the following picture, directly on your main screen on iOS.

The script is in attachment.
The only thing to change is the following line :

const API_URL = "https://enoxys.fr/stellar/api/me?token=YOURAPIKEYONTHEGAME"
You have to replace YOURAPIKEYNTHEGAME by the API key provided on the settings —> account.

Then you just have to install the widget on the main menu, choose the largest size for better view, and select the script, and « open script » for the click action —> it will force refresh (and call the API).