import string, random, discord 
from discord.ext import commands

bot = commands.Bot(command_prefix='!')
TOKEN = "MTAwNDgwMjc4NDk3NTEyNjYwMA.Gpzs-x.ue0N9DTLLACpXUe5p7jE4t1KsDx4tgSePHZX8Q"

@bot.command()
async def nitro(ctx):
    code = "".join(random.choices(string.ascii_letters + string.digits, k=16))

    await ctx.send("https://discord.gift/" + code)

bot.run(TOKEN)