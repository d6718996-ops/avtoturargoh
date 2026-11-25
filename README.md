mkdir avtoturargoh-at && cd avtoturargoh-at
git init
echo "# Avtoturargoh axborot tizimi" > README.md
echo "Ish tartibi: kunduzgi - 08:00-20:00, tungi - 20:00-08:00" >> README.md
printf "__pycache__/\n*.log\n.env\n" > .gitignore
git add README.md .gitignore
git commit -m "chore: loyiha tuzilmasi yaratildi"
