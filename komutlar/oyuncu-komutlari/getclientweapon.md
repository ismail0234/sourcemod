---
description: Oyuncunun elinde tuttuğu silahın adını almanızı sağlar.
---

# GetClientWeapon

{% tabs %}
{% tab title="Kullanım" %}
```cpp
char weapon[64];
GetClientWeapon(client, weapon, sizeof(weapon));
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
void GetClientWeapon(int client, char[] weapon, int maxlen);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | Oyuncu numarası |
| weapon | char\[\] | Oyuncunun silahının depolanacağı değişken |
| maxlen | int | Oyuncunun silahın adının uzunluğu |

#### Geri Dönüş Değeri

{% hint style="warning" %}
Bu fonksiyon geriye veri döndürmez.
{% endhint %}

