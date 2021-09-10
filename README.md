**2DSIM - SetAsync**

2DSIM is a system inspired by Renpy that runs through discord bots. You can create visual / text-based novels through discord using python and discord.py / nextcord.py.

Note: Despite the name, this game does not revolve around 2D, the name 2DSIM is an inside joke that I will not explain on here.
Read the wiki for a more in depth documentation.

To create a game edit the "GAME.py" module according to your needs, at the moment this is very primitive.

__I haven't really done much research into the effect's of discord.py's archivation, at the moment nextcord.py seems to be maintained and functional. Open to suggestions.__ 

Example Game:
```py
main = [

    [
        "dialog",
        "Alex",
        "Hello, how are you?"
    ]

    [
        "choice",
        "**You...**",
        "What is your response?",
        {

            "I'm good thank you!": [

                [
                    "dialog",
                    "Alex",
                    "Great!"
                ]

            ],

            "I hate you, go away.": [

                [
                    "dialog",
                    "Alex",
                    "Fine... never liked you anyway."
                ]

            ]

        }
    ]
]
```
