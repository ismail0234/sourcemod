---
description: Oyuncunun birçok steamId bilgisinden bir tanesini almanızı sağlar.
---

# GetClientAuthId

{% tabs %}
{% tab title="Kullanım" %}
```cpp
char steamId[32];
GetClientAuthId(client, AuthId_SteamID64, steamId, sizeof(steamId));
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool GetClientAuthId(int client, AuthIdType authType, char[] auth, int maxlen, bool validate);
```
{% endtab %}

{% tab title="authType" %}
Bu parametre aşağıdaki 4 değerden birini almaktadır.

| Değer |  Örnek |
| :--- | :--- |
| AuthId\_Engine | Oyuna özel benzersiz bir kimlik |
| AuthId\_Steam2 | STEAM\_1:0:93611705 |
| AuthId\_Steam3 | \[U:1:187223410\] |
| AuthId\_SteamID64 | 76561198147489138 |
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | İstemci numarası |
| authType | AuthIdType | Alınacak kimlik türü |
| auth | char\[\] | Steam Id bilgisini depolar |
| maxlen | int | Steam Id max karakter uzunluğu |
| validate |  bool | Arka uç doğrulaması yapılacakmı |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **bool** değerinde **başarılı/başarısız** döndürmez.
{% endhint %}

