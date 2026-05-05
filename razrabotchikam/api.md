# API

[API](https://ru.wikipedia.org/wiki/API) (программный интерфейс приложения) позволяет организовать интеграцию вашего собственного приложения с сервисом [Впостер](https://vposter.ru/).

## Ключ доступа <a href="#parametry" id="parametry"></a>

Ключ доступа можно получить в кабинете сервиса в разделе "Разработчикам" или по [ссылке](https://vposter.ru/dev).

## Документация <a href="#sintaksis-zaprosov" id="sintaksis-zaprosov"></a>

{% embed url="https://vposter.ru/api" %}
Документация Swagger
{% endembed %}

{% openapi-operation spec="vposter-api" path="/v3/method/users.getMe" method="get" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/groups.getMy" method="get" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/uploads.uploadFile" method="post" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/posts.getList" method="get" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/posts.getById" method="get" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/posts.create" method="post" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/posts.edit" method="put" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/posts.delete" method="delete" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/posts.pause" method="post" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/posts.resume" method="post" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/stories.getList" method="get" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/stories.getById" method="get" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/stories.create" method="post" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/stories.edit" method="put" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/stories.delete" method="delete" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/stories.pause" method="post" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/stories.resume" method="post" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/dictionary.getKktu" method="get" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}

{% openapi-operation spec="vposter-api" path="/v3/method/dictionary.getCountries" method="get" %}
[OpenAPI vposter-api](https://vposter.ru/api/swagger.yaml)
{% endopenapi-operation %}
