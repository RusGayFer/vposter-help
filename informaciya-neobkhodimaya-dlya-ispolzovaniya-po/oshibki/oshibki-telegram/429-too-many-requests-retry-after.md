# 429 - Too Many Requests: retry after

При отправке запросов через API Telegram может возвращаться следующая ошибка:

{% hint style="danger" %}
Ошибка от Telegram #429 - Too Many Requests: retry after 3
{% endhint %}

## Решение проблемы <a href="#reshenie-problemy" id="reshenie-problemy"></a>

Подождать, пока ошибка сама пропадет. В ошибке указывается, через сколько секунд можно повторить. Обычно она выходит при массовом постинге.
