# link_shortener

Endpoint: 

POST /AUTH/SIGN-UP - регистрация нового пользователя

POST /AUTH/SIGN-IN - вход в систему, возвращает JWT токен для послдующих запросов

POST /links - создаёт новую сокращенную ссылку

GET /links - возвращает список всех созданных ссылок пользователя
GET /links/{short_code} - возвращает информацию по конкретной ссылке

DELETE /links/{short_code} - удаляет оригинальную ссылку

GET /redirect/{short_code} - возвращает оригинальную ссылку

GET /links/{short_code}/stats - возвращает статистику использования конкретной ссылки пользователя

![image](https://github.com/user-attachments/assets/9031ce5f-858a-4ea7-80d4-02a8dcab1bc7)




