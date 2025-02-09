[Návod v češtině](https://github.com/Zasilkovna/virtuemart3#modul-pro-virtuemart-3--joomla-3)

# Module for VirtueMart 3 + Joomla 3

### Download module

[Actual version 1.1.8](https://github.com/Zasilkovna/virtuemart3/archive/v1.1.8.zip)

### Installation

The current version of the module is available on the github in the repository https://github.com/Zasilkovna/virtuemart3. 
To download the module directly as a zip package, click the button **Clone or download** and choose an option **Download ZIP**.

To install the plug-in, you need to do the following:

- log in to Joomla administration (usually at {domain} / administrator)
- in the top menu, select ** Extensions / Manage / Install **
- in the tab **Upload Package File**  drag the installation package to the marked section, or click **Or Browse for file** and select the installation package file

### Plugin configuration

#### Basic configuration

- In the Joomla administration, select in the top menu **VirtueMart** / **Configuration**.
- Select in the left menu **CONFIGURATION** / **PACKETA**.
- Go to the ** Configuration ** tab.
- Fill in **API key** which you can find in the [client section] (https://client.packeta.com/cs/support/) » Client support.
- Enter ** E-shop ID ** - the sender name you have set in the client section of your [sender] (https://client.packeta.com/cs/senders/).


##### General rules

- **default price** - the shipping price applies if the country-specific default price is not filled
- **Maximum weight** - for orders with a larger weight, the Packeta shipping method will not be offered in the cart
- **free shipping** - if the order price is higher, free shipping

#### Configuring Weighting Rules and Pricing

Pro každou podporovanou zemi je možné nastavit:
- ** default price ** - the price will be applied if you do not fill in the pricing rules, or the order weight exceeds the set weighting rules for a particular country
- ** free shipping ** - if the order price is higher, free shipping
- ** Weight rules ** - click ** Add ** to set prices for different order weights. To cancel the weight rule, click the ** Remove ** button

Save the configuration with the ** Save ** button in the upper left corner of the page.
Next, select ** VirtueMart ** / ** Shipment Methods ** in the top menu and add a new shipping method. The added method must have ** Shipment Method ** set to ** VM3 Mail **

#### List of orders

- In the Joomla administration, select the item in the top menu **VirtueMart** / **Configuration**.
- Select in the left menu **CONFIGURATION** / **PACKETA**.
- Go to the ** Orders ** tab.
- To export shipments, check the checkbox in the first column of the order and then click the ** CSV ** button (when exporting to a csv file) or the ** Submit Shipments ** button (in case of direct submission).

- Export shipments to CSV file:
    - Mark orders (by checkbox) that you want to export to CSV file.
    - Above the list of orders, click the ** CSV ** button to save the file.

- Direct submission (via API):
    - Mark orders (checkbox) that you want to send to the Packeta.
    - Above the list of orders, click the ** Submit Shipments ** button.
    - To print labels, check the checkbox in the ** Print Labels ** column of the order, then click the ** Print Labels ** button above the order list.
	
### Module information

#### Supported languages:

- czech
- english

#### Supported versions:

- VirtueMart 3 + Joomla 3
- If you have trouble using the module, please contact us at [technicka.podpora@zasilkovna.cz](mailto:technicka.podpora@zasilkovna.cz)

#### Functions provided:

- Widget integration in eshop cart
- Set different prices for different target countries
- Setting prices according to weight rules
- Free shipping from the specified price or weight of the order
- Export shipments to csv file, which can be imported in [client section](https://client.packeta.com/)
- Přímé podání zásilek do systému Zásilkovny a tisk štítků
- Direct orders submission to the Packeta system and labels printing


# Modul pro VirtueMart 3 + Joomla 3

### Stažení modulu

[Aktuální verze 1.1.8](https://github.com/Zasilkovna/virtuemart3/archive/v1.1.8.zip)

### Instalace

Aktuální verze modulu je dostupná na githubu v repository https://github.com/Zasilkovna/virtuemart3. 
Pro přímé stažení modulu jako zip balíčku je potřeba kliknout na tlačítko **Clone or download** a zvolit možnost **Download ZIP**.

Pro instalaci plug-inu je potřeba provést následující kroky:

- přihlašte se do administrace systému Joomla (obvykle na adrese {doména}/administrator)
- v horním menu vyberte položku **Rozšíření / Spravovat / Instalovat**
- v záložce **Upload Package File**  přetáhněte instalační balíček do vyznačené části, nebo klikněte na tlačítko **Or Browse for file** a vyberte soubor s instalačním balíčkem

### Konfigurace plug-inu

#### Základní konfigurace

- V administraci systému Joomla vyberte v horním menu položku **VirtueMart** / **Configuration**.
- V levém menu vyberte položku **CONFIGURATION** / **PACKETA**.
- Přejděte na záložku **Konfigurace**.
- Vyplňte **API klíč** který naleznete v [klientské sekci](https://client.packeta.com/cs/support/) » Klientská podpora.
- Zadejte **Identifikátor eshopu** - označení odesílatele které máte nastaveno v klientské sekci u vašeho [odesílatele](https://client.packeta.com/cs/senders/).


##### Obecná pravidla 

- **Výchozí cena** - cena za přepravu se použije v případě, že není vyplněna výchozí cena u konkrétní země
- **Maximální váha** - u objednávek s větší hmotnostní nebude v košíku přepravní metoda Zásilkovna nabízena
- **Doprava zdarma** - pokud bude cena objednávky vyšší bude doprava zdarma

#### Konfigurace váhových pravidel a cen

Pro každou podporovanou zemi je možné nastavit:
- **Výchozí cena** - cena se použije pokud nevyplníte cenová pravidla, nebo hmotnost objednávky přesáhne nastavená váhová pravidla pro konkrétní zemi
- **Doprava zdarma** - pokud bude cena objednávky vyšší bude doprava zdarma
- **Váhová pravidla** - kliknutím na tlačítko **Přidat** můžete nastavit ceny pro různé váhy objednávky.  Pro zrušení váhového pravidla klikněte na tlačítko **Odebrat**

Konfiguraci uložte tlačítkem **Save** v levém horním rohu stránky.
Dále je potřeba zvolit v horním menu položku **VirtueMart** / **Shipment Methods** a přidat novou metodu dopravy. Přidaná metoda musí mít parametr **Shipment Method** nastavený na **Zasilkovna VM3**

#### Seznam objednávek

- V administraci systému Joomla vyberte v horním menu položku **VirtueMart** / **Configuration**.
- V levém menu vyberte položku **CONFIGURATION** / **PACKETA**.
- Přejděte na záložku **Objednávky**.
- Pro export zásilek je potřeba zaškrtnout checkbox v prvním sloupci u objednávky a poté kliknout na tlačítko **CSV** (při exportu do csv souboru) nebo na tlačítko **Podat zásilky** (v případě přímého podání).

- Export zásilek do CSV souboru:
    - Označte objednávky (zaškrtnutím checkboxu) které chcete exportovat do CSV souboru.
    - Nad seznamem objednávek naleznete klikněte na tlačítko **CSV** a soubor uložte.

- Přímé podání zásilek (přes API):
    - Označte objednávky (zaškrtnutím checkboxu) které chcete odeslat do Zásilkovny.
    - Nad seznamem objednávek naleznete klikněte na tlačítko **Podat zásilky**.
    - Pro tisk šítků je zaškrtněte checkbox ve sloupci **Tisk štítků** u příslušné objednávky a poté klikněte na tlačítko **Vytisknout štítky** nad seznamem objednávek.

### Informace o modulu

#### Podporované jazyky:

- čeština
- angličtina

#### Podporované verze:

- VirtueMart 3 + Joomla 3
- Při problému s použitím modulu nás kontaktujte na adrese [technicka.podpora@zasilkovna.cz](mailto:technicka.podpora@zasilkovna.cz)

#### Poskytované funkce:

- Integrace widgetu v košíku eshopu
- Nastavení různé ceny pro různé cílové země
- Nastavení cen podle váhových pravidel
- Doprava zdarma od zadané ceny nebo hmotnosti objednávky
- Export zásilek do csv souboru, který lze importovat v [klientské sekci](https://client.packeta.com/)
- Přímé podání zásilek do systému Zásilkovny a tisk štítků