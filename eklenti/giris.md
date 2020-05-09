---
description: Sourcemod eklentisinin standart kullanılan yapısını anlatır.
---

# Giriş

Bir sourcemod eklentisi oluşturabilmeniz için aşağıdaki iskelet yapıyı kullanmanız gerekmektedir. İskelet yapısı eklentinizin temelidir.

{% tabs %}
{% tab title="İskelet Yapı" %}
```cpp
#include <sourcemod>
#include <sdktools>
#include <sdkhooks>

#pragma newdecls required

public Plugin myinfo = 
{
	name        = "Eklenti Adı",
	author      = "Eklenti Yazar Adı",
	description = "Eklenti Açıklaması",
	version     = "v1.0.0",
	url         = "https://www.botbenson.com"
};

public void OnPluginStart()
{

}
```
{% endtab %}
{% endtabs %}

Bu iskelet yapı içerisinde aşağıdaki durumları gerçekleştirir.

* Eklentinize 3 adet kütüphane ekler.
* Eklentinizin yeni söz dizimi ile derlenmesi gerektiğini söyler.
* Eklentiniz hakkında bazı bilgileri barındırır.
* Eklentizin aktif edildiğinde çalışacak olan bir kancayı barındırır.

