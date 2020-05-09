---
description: Oyuncunun mevcut karakter modelini almanızı sağlar.
---

# GetClientModel

{% tabs %}
{% tab title="Kullanım" %}
```cpp
char model[64];
GetClientModel(client, model, sizeof(model));
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
void GetClientModel(int client, char[] model, int maxlen);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | Oyuncu numarası |
| name | char\[\] | Oyuncunun modelinin depolanacağı değişken |
| maxlen | int | Oyuncunun modelin uzunluğu |

#### Geri Dönüş Değeri

{% hint style="warning" %}
Bu fonksiyon geriye veri döndürmez.
{% endhint %}

