friends.getRelativesV2

$description
Получить описание связей пользователя.

$params#uid
Идентификатор пользователя

$params#friend_ids
Список идентификаторов друзей, описание связи с которыми мы хотим получить.

$params#reltypes
Список типов запрашиваемых связей, разделённых запятой.

$params#anchor
Идентификатор постраничного вывода.

$params#direction
Направление постраничного вывода.

$params#count
Количество возвращаемых результатов.

$additional
Только один из параметров 'friend_ids', 'reltypes' должен быть указан.