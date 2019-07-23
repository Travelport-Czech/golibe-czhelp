# E-mailové notifikace

V menu **Notifikace** najdete nastavení e-mailových zpráv, které GOL IBE automaticky odesílá.

Všechny notifikace, které používáte, již máte přednastavené.

V přehledné tabulce nastavených notifikací uvidíte následující sloupce, které zobrazují, komu jsou e-maily doručovány.

| **Komu** | Popis |
| :--- | :--- |
| **Zákazníkovi** | Doručováno klientovi, který vložil svou adresu během rezervačního procesu. |
| **Dealerovi** | Doručováno dealerovi, jehož emailová adresa je nastavena v menu **Dealeři**. |
| **Agentuře** | Doručováno agentuře na adresu uvedenou v **Agentura -&gt; Nastavení agentury**. |
| **Konfigurátorovi** | Doručováno administrátorovi systému \(jen pro účely ladění, nebo konzultací\). |

V případě zájmu o změnu tohoto nastavení klikněte na **DORUČENÍ**.

{% hint style="warning" %}
GOL IBE odesílá Vaším jménem zákazníkům e-mailová potvrzení. Například jste agentura abtravel a zákazník dostane potvrzení o rezervaci z emailové adresy info@abtravel.com.

Protože ale v dnešní době maximální ochrany před spamem můžete mít na e-maily ze své strany nasazeny různé ochrany, nemusí být e-maily z GOL IBE zasílané Vaším jménem dobře doručovány zákazníkům.

Proto je potřeba mít nastaveny své e-maily / doménu následujícím způsobem:

Pokud používáte SPF, pak v nastavení domény povolte náš mailserver:

**v=spf1 mx mx:golibe.com ~all**

Pokud má již vaše doména SPF záznam, musíte přidat SPF do existujícího záznamu následujícím způsobem.

**include:golibe.com**

Do domény si vždy přidejte CNAME záznam:

**golibe.\_domainkey.agentura.cz CNAME golibe.\_domainkey.golibe.com**
{% endhint %}

