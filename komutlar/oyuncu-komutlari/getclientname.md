---
description: Oyuncunun adını almamızı sağlar.
---

# GetClientName

{% tabs %}
{% tab title="Kullanım" %}
```cpp
char name[64];
GetClientName(client, name, sizeof(name));
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool GetClientName(int client, char[] name, int maxlen);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | Oyuncu numarası |
| name | char\[\] | Oyuncunun adının depolanacağı değişken |
| maxlen | int | Oyuncunun adının uzunluğu |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **bool** değerinde **başarılı/başarısız** döndürür.
{% endhint %}

