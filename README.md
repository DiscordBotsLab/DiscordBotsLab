# Hello Discord :wave:
```ts
class DiscordBotsLab extends DiscordGamesLab {
    public repos: Array<DiscordBots>
    public api: string = 'Work in progress'
    public server: string = ''

    readonly description: string = 'Creating Discord bots for the future'
    readonly preferredLanguages: Array<string> = ['js', 'ts']
    readonly canworkin: Array<string> = ['html', 'css', 'js', 'ts']

    constructor(team: Array<TeamMember>) {
        super(team)
    }
}
```
