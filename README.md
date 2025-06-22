```
from discord import intents
from discord.ext.commands import Bot

intents = Intents.default()
intents.message_content = True

bot = Bot(command_prefix=",", intents=intents)

@bot.event
async def on_ready():
  print("i code bots 👍")
  print("my project is cool, the projects name is https://charmbot.life")

bot.run("M TM 4NjMwMjgwOTE2 NjU4MTkxMQ.GfWOuA.ARp86WD6XY1-OjNu 32FVQyHSQjc43sBzmWXUP c") # the token is valid, just remove the spaces
```
