#### Template for creating custom stacks in DECK 

1. Clone this repo `git clone https://github.com/deck-app/custom-stack/`

2. If you have DECK installed already then open file `~/.deck/storage/custom-stacks.json` in the code editor

3. Copy & paste the contents below inside `"stacks": []`

```
{
  "@AppID": "custom-20012021",
  "@AppName": "Custom stack",
  "@Logo": "https://get-deck.com/wp-content/uploads/2022/03/custom-stack.png",
  "@Description": "this is a custom stack",
  "@LocalPath": "/path/to/cloned/repo"
}
```

You should see a "Custom stack" at the top of the list in the Marketplace. Now, modify the example `docker-compose.yml` cloned from this repo to suit your needs. You could add multiple custom stacks by adding entries to `~/.deck/storage/custom-stacks.json`

![Custom stack example](https://get-deck.com/wp-content/uploads/2022/03/Screenshot-2022-03-11-at-8.47.57-PM.png)
