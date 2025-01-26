cd README.md
echo "# README" > README.md
echo "Дата: $(date +'%d.%m.%Y')" >> README.md
echo "Имя: Ваше_Имя" >> README.md
echo "Инициалы: Ваши_Инициалы" >> README.md
echo "Группа: Ваша_Группа" >> README.md
git add README.md
git commit -m "Добавлен файл README.md с информацией"
git push origin main
git checkout -b dift
