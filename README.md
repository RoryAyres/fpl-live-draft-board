# fpl-live-draft-board
A small script that can be connected to a Google Sheet that refreshes draft picks live.

The only inputs required are a Google Sheet URL and your League ID. The league administrator can grab your league code by going to Edit League page. It will be the value in the URL: https://draft.premierleague.com/league/{LEAGUE-ID-HERE}/edit. I am not sure if there is another easy way to find this.

Create a Google Sheet and add the URL to the script. You will have to authenticate and allow Colab to access the sheet.
A new sheet tab for your draft should generate when the script runs. If a tab already exists in the sheet named the league id it will use that tab.

The script does not format any cells, but you can preformat the sheet if you know the layout, I suggest running a mock for this. If you want to test on a mock draft the league ID for them is the number in the name of the league: "Mock XXXXX".

The script was written by Chat GPT, I have a rudimentary understanding of Python and a technical profession so could understand what is going on with the code to debug, but other than that Chat GPT did the work.
