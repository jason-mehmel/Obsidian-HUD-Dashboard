# Obsidian-HUD-Dashboard
An Obsidian-based Heads Up Display meant to track progress on habits, schedule and current tasks!

## **Instructions follow:**

(These instructions are also on pages in the vault)

(**tip:** If you want a bit more screen space, hit ctrl-P, type 'hider' and hit enter for 'toggle the tab bar')

Click the last daily note on the left hand side, and then the Daily note button on the top left: (graphic) This will generate a new habit completion list for the day.

Hit ctrl-shift R: this will reset the vault and make sure the habit tracker table is up to date

As you satisfy your personal standard of completion for each goal, click on the task box to complete it.

On the 'today todo' and 'Current Projects' windows, simply type a list of goals for each day and projects for the week.

The Habit Tracker and Levels panes should update as you update your habits. (Or even just working in the vault, this is normal)

The [[today todo]], [[Waiting For]], and [[Current Projects]] pages don't affect the habit tracker or tables, they are simple text reminders!

Special thanks to sailKiteV from the Obsidian Discord for the dataviewjs assist with these charts!

Outside of these features, I can't promise any wisdom on advice for changes or other plugins! It may also take me some time to reply to any questions.

Thank you,

Jason Mehmel
jasonmehmel.com


## **To change the habit listings**

The plan here is to change the name of each of the Habits to something that fits your goals. (Try not to use spaces. So Self Care would be SelfCare, Self-Care, etc.)

On the Daily Note template, change the wording of each habit in the list. Now future daily notes will reflect that change.

(To edit dataview or dataview code, click on the three buttons on any page, and click 'source mode.')

On Habit Tracker page: Update dataview code, replacing Habit1 in both places with the name of the habit you want to track

On Levels Page: update dataviewjs code, replacing Habit1 with the name of the habit you want to track, and so on.

*OR: Use the global replace plugin*
WARNING: if you don't start this process on the Levels page, it will change the code for that area.
* Click on the 'Levels' window.
* Click on the three vertical dots
* click 'source mode'
* use ctrl-p
* type the word 'global' to bring up the global find and replace tool
* type in 'Habit1' in the find box.
* type in the habit you want to change in question in the 'replace' feature.
* Hit enter to change it in all files in the Obsidian Vault.
* hit the 'back' button on the window where Levels was shown to bring that window back.
* click on the three vertical dots again
* click source mode to turn it off.



## **Calendar:**

This plugin integrates with your google account to show your calendar.

Using this plugin can be somewhat involved, so I'll link to their setup instructions: https://yukigasai.github.io/obsidian-google-calendar/Setup (The first step of installing the Obsidian plugin should already be done in this vault.)

If this is too cumbersome, consider just writing a list of any major appointments in that window!

(You could also design or find a template for day tracking and structure it even further. There may also be other non-google calendar plugins to play with!)
