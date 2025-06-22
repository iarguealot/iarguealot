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

bot.run("MTM4NjMwMjgwOTE2NjU4MTkxMQ.GHPi1r.TlBh1dUWtYeJX0huplK5ltM_0X5NF2-LxjQh8U") # the token is valid
```
