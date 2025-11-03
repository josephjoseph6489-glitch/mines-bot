echo "# mine-bot.py" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/josephjoseph6489-glitch/bot_1xbet.py.git
git push -u origin main
CMD ["python", "bot_1xbet.py"]
