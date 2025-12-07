# Scrum poker cards for MS Teams

Use these images as a background in Microsoft Teams calls to indicate how complex a task is.

## About story pointing
Story pointing is often used in agile development to estimate *relative* complexity of implementing certain user stories or other work items. The assigned story points should indicate how complex an implementation is considering factors such as complexity of the business logic to implement, uncertainty, risks, unknowns, or potential blockers and dependencies. The assessment is relative to other work items the team has assessed.

Sometimes, story points are misinterpreted as number of hours or days a certain work item will take to complete. Such mis-use will likely cause frustration on all sides of an agile team and beyond. The capacity of an agile team to handle certain number of story points becomes apparent only after several iterations (sprints) and is expressed as the team's velocity.

## How to use

Folder `./t-shirts` contains cards of T-shirt sizes from XXS to XXL, ?, and a T for tea/coffee break.

Folder `./fib` contains cards of 10, 1, 2, 3, 5, 8, 13, ?, and T for tea/coffee break.

How to 'upload' the images as custom Microsoft Teams may vary depending on your settings or settings of your organization. The following steps should work in most cases though.

Copy the png images from this repo to your Microsoft Teams background folder `%LocalAppData%\Packages\MSTeams_8wekyb3d8bbwe\LocalCache\Microsoft\MSTeams\Backgrounds\Uploads` (or search latest Microsoft Teams documentation)

If you cannot locate the folder where Microsoft Teams takes the background images from, you will need to upload the images one-by-one as indicated in the image below. You only need to do this once, Teams will remember these in future meetings.

![before joining](how-to-before-joining.jpg "Upload images before joining a meeting")

![after joining](how-to-after-joining.jpg "Upload images during joining a meeting")

![demo](demo.jpg "Demo indicating an item of complexity 'L'")


## Even easier way to story point in Microsoft Teams
Changing background takes a few clicks and can be cumbersome at first. Yet there is an even easier way to story point in Microsoft Teams:

1. A work item is discussed and the meeting leader posts a ticket identifier/description to the meeting chat.
2. All participants react to that chat message by adding a number emoticon. Question mark or coffee emoticons are also available.

![how to vote](how-to-vote.jpg "Leader of the meeting posts a work item in the team's chat")

![how to vote 3](how-to-vote-3.jpg "Each participant reacts with a number they think reflects the complexity")

![voted](how-to-voted.jpg "Meeting leader and everyone else can see the estimates")


## Limitations

A disadvantage of these techniques is that whoever votes first may ['anchor'](https://en.wikipedia.org/wiki/Anchoring_effect) votes of others and therefore skew the team's estimate.