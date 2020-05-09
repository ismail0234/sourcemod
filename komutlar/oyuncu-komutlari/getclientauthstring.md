---
description: Oyuncunun Steam'e özel id bilgisini almanızı sağlar
---

# GetClientAuthString

{% tabs %}
{% tab title="Kullanım" %}
```cpp
char steamId[32];
GetClientAuthString(client, steamId, sizeof(steamId));
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool GetClientAuthString(int client, char[] steamId, int maxlen, bool validate);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | İstemci numarası |
| steamId | char\[\] | Steam Id bilgisini depolar |
| maxlen | int | Steam Id max karakter uzunluğu |
| validate |  bool | Arka uç doğrulaması yapılacakmı |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **bool** değerinde **başarılı/başarısız** döndürmez.
{% endhint %}

