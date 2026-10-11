MOJE STYLISTKA — první prototyp

Co funguje:
- přidávání jednotlivých kusů oblečení z fotografie
- lokální ukládání fotografií a záznamů v IndexedDB
- kategorie, názvy, barvy, poznámky a oblíbené kusy
- jednoduché návrhy kombinací podle kategorií
- ukládání outfitů a označování oblíbených
- profilová fotografie a volba stylu
- nápady, co by se do outfitu dalo dokoupit
- žádné reklamy, žádné předplatné, žádný externí AI endpoint

Důležité limity:
- Tohle je první funkční prototyp, ne hotová nativní iOS aplikace.
- Zatím neumí realisticky převléct uživatelku na její fotografii; ukládá profilovou fotografii a zobrazuje skutečné fotky kusů vedle sebe.
- Návrhy outfitů jsou založené na jednoduchých pravidlech, nikoli na generativní AI.
- Data zůstávají v úložišti prohlížeče. Smazání dat webu/prohlížeče je může odstranit.
- Pro instalaci jako PWA potřebuje aplikace HTTPS hosting. Lokální HTML lze nejprve otevřít na počítači pro testování.

Testování:
1. Rozbal ZIP.
2. Otevři index.html v moderním prohlížeči.
3. Pro přidání na plochu iPhonu je třeba aplikaci umístit na HTTPS hosting, otevřít URL v Safari a zvolit Sdílet > Přidat na plochu.
4. Nikam nenahrávej soukromé fotografie, pokud nechceš; prototyp nepoužívá serverové úložiště.

Bezpečnostní doporučení:
- Pro fotografii postavy zvol oblečení, ve kterém se cítíš pohodlně, a vyhni se zbytečně identifikujícím detailům pozadí.
- Nejde o profesionální módní poradenství ani skutečný virtuální fitting.
