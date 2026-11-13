# reseller-toolbelt

Werkzeuge für den Weg vom China-Agent zur verkauften Ware: bestellen, Haul
exportieren, Versandkosten vorher durchrechnen, Artikel beschreiben, Bestand
führen.

Alle vier Projekte liegen unverändert in einem eigenen Ordner und bringen ihre
vollständige Git-Historie mit.

| Ordner | Was es tut | Art |
|---|---|---|
| `haul-exporter` | Bestellungen von GTBuy, ACBuy und CNFans als TSV exportieren, direkt einfügbar in Google Sheets | Chrome-Extension |
| `shipping-simulator` | Pakete im Warenlager gedanklich gruppieren und Versandkosten vorher durchspielen | Chrome-Extension |
| `adgen` | Produktfoto plus Stichworte zu einem fertigen Listing für eBay, Kleinanzeigen, Vinted und Depop | BYOK-Web-App |
| `buy2sell` | Flohmarkt-Hauls, Artikel und Verkaufspreise verwalten, Etiketten drucken | Web-App |

Die drei kleinen Werkzeuge laufen ohne Konto und ohne Cloud. `adgen` braucht
einen eigenen API-Schlüssel des Modellanbieters, gespeichert wird er
verschlüsselt.

Für alles darüber hinaus, also Lager, Multi-Plattform-Listings und
Automatisierung, gibt es das kommerzielle ReFlow.

## Lizenz

MIT, siehe `LICENSE`.
