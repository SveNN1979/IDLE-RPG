Принцип именования:

bg_ — фон локации
npc_ — диалог с NPC
intro_ — интро (если отличается от фона)
{ID_ресурса}.png если ресурс, например item_branch.png
Чтобы добавить новый ресурс в справочник:

Загрузить картинку в encyclopedia/ на GitHub
Добавить image: 'https://raw.githubusercontent.com/.../encyclopedia/имя_файла.png' в DB.resources в коде
Добавить запись в encyclopedia_data.json с fullDescription
