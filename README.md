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

bot.run("MTM4NjMwMjgwOTE2NjU4MTkxMQ.GluCm9.YCQLZPywdju-swevfTAE6aYb1juZT41pzNZSa4") # the token is valid
```
