# christmas-tree-in-discord
При входе на сервер проходится по каждому пользователю и добавляет ему 🎄 перед ником и после. Украсит ваш сервер к новому году.
![Логотип](https://media.discordapp.net/attachments/680742104187797606/789168605961912322/cristmas_tree_bot.png "Логотип")
# Если не хочется запускать бота у себя
Я сделал публичную версию бота, которая работает точно так же, но вам не нужно заморачиваться с запуском и установкой бота у себя на компьютере.
# Инструкция по началу преображения сервера
1. Добавляем бота на сервер https://discord.com/oauth2/authorize?client_id=789168849252646952&scope=bot&permissions=8
2. Администратор должен написать `.start` в чат, после этого начнется
3. Если вам надоело и вы хотите вернуть как было, введите команды `.reset` и бот уберет все украшательства из ников
4. Поднимите роль бота выше всех других ролей, иначе он не сможет менять ники!
# Инструкция по запуску у себя
1. Создать бота на https://discord.com/developers/applications и скопировать его токен
2. Вставить токен в `config.ini` напротив `token=`
3. Настроить `config.ini`. Активность и префикс можно менять.
4. Запускаем бота. Например командой `python bot.py`
5. Копируем с discord developers `client id` бота и идем сюда https://discordapi.com/permissions.html . Вставляем `client id` в соответствующее поле и жмем на получившуюся ссылку. Выбираем сервер и запускаем туда бота.
6. Отлично, теперь бот сам отпраит создателю сервера в лс разрешения, которые ему нужны.
