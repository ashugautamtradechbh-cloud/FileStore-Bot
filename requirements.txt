import nest_asyncio
nest_asyncio.apply()

from pyrogram import Client

bot = Client("MahiruMasterBot", 
             api_id=32467601, 
             api_hash="4c4f019c3eacb6794ec5cdcc8030595e", 
             bot_token="8859491458:AAGKjcuFvWQxBpj61mMGZbRTWu3XafbCutw",
             sleep_threshold=10)

print("Bot starting...")
bot.run()
