# Money Splitter
## Technologies
* `TypeScript` frontend
* `Bootstrap`
* `Yesod` backend
* DB: `Redis`? Some key-value database, creating tables for each room is overkill

## Functionality
* Create/enter room
	--> allow named rooms
* Show other users' payments
* Room auto-destructs after x hours

## Interface
* Mobile-driven development

## Algorithms
* Minimize the number of splits

## Security
* Limit number of attempts @ creating/entering room
* Cross-site scripting attacks
* Escape database queries

## Software Engineering
* Write in pure, functional style as best possible
