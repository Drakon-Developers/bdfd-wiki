# $allowUserMentions
Enables user pings only for the provided user IDs, while the user not provided will be 'fake pinged' *(the user will be pinged, but user will not be notified)*.

## Usage
```
$allowUserMentions[userIDs]
```

### Breakdown
- `userIDs` - The users that can be pinged, leave empty to disable pings for every user. Separate user IDs using `;`.

## Example
```
$nomention
$allowUserMentions[]
Hi <@696368083517964288>! I mentioned you, but you didn't get pinged.
```
