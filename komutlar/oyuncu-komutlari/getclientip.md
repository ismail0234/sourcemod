---
description: Oyuncunun ip adresini almanızı sağlar.
---

# GetClientIP

{% tabs %}
{% tab title="Kullanım" %}
```cpp
char ip[64];
GetClientIP(client, ip, sizeof(ip));
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool GetClientIP(int client, char[] ip, int maxlen, bool port);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | Oyuncu numarası |
| ip | char\[\] | Oyuncunun ip adresinin depolanacağı değişken |
| maxlen | int | Oyuncunun ip adresinin uzunluğu |
| port | bool | Oyuncunun portu ip adresinden kaldırılsınmı ? |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **bool** değerinde **başarılı/başarısız** döndürür.
{% endhint %}

