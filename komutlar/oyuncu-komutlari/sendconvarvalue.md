---
description: Belirli oyuncuların convar değerini değiştirmek için kullanmanızı sağlar.
---

# SendConVarValue

Bu fonksiyon ile bir oyuncuya **sv\_enablebunnyhopping 1** yetkisi verebilirsiniz. Bu sayede sadece bu oyuncu bunny yapabilecektir. 

{% tabs %}
{% tab title="Kullanım" %}
```cpp
ConVar bunnyHop = FindConVar("sv_autobunnyhopping");
if(SendConVarValue(client, bunnyHop, "1")) {
    // Kullanıcıya özel convar değişimi başarılı
} else {
    // Kullanıcıya özel convar değişimi başarısız
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool SendConVarValue(int client, ConVar convar, const char[] value);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | Oyuncunun numarası |
| convar | ConVar | Sunucu üzerindeki convar değeri |
| value | char\[\] | Yeni Değer |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **bool** değerinde **başarılı/başarısız** döndürür.
{% endhint %}



