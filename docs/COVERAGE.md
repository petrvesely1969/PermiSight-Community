# Coverage and evidence / Pokrytí a důkazy

PermiSight checks supported sources on macOS and Windows. It does not claim a
complete inventory of every AI product. English and Czech are supported in the app.
Operating-system permissions and platform APIs affect what can be established.

| Observation | What it supports | What it does not establish on its own |
| --- | --- | --- |
| Application registration or bundle | A trace of an application | That its file still exists, is authentic, or is running |
| File and identity checks | Evidence about that file, with the verification state shown | That every name match is an identified AI product |
| Local model file | Presence of a recognized format or candidate model file | A loaded model, a running service, or model safety |
| Extension files or configuration | Evidence about an installed or configured component | That the extension is enabled or was used |
| Declared AI capability | A documented or technically declared possibility | That the user has a license, enabled it or used it |
| Supported runtime evidence | The activity described by that specific evidence | What content an application read or transmitted |

Nonstandard paths and ports can be discovered where a supported collector can
read an applicable configuration or runtime source. This is not a promise of
whole-disk or arbitrary-port discovery. Restricted, failed and unexamined areas
must remain visible. Catalog membership is not the same as physical testing of
every product version and installation layout.

The first release provides local read-only inspection, result export, manual
signed-catalog checks and optional report submission with preview and consent.
It does not block software, change its permissions, classify malware or inspect
the contents of user communications. Remote business management, mobile-device
inspection and network-wide AI discovery are future directions.

## Česky

PermiSight kontroluje podporované zdroje v macOS a Windows. Rozsah závisí
na přístupových právech a informacích dostupných z dané platformy.

- Registrace aplikace je stopa; sama nepotvrzuje přítomnost souboru ani běh.
- Nalezený model není důkazem jeho načtení, bezpečnosti nebo běžící služby.
- Nainstalovaný či nakonfigurovaný doplněk nemusí být zapnutý ani používaný.
- Deklarovaná AI funkce neprokazuje licenci, zapnutí ani skutečné použití.
- Podporované nastavení může napovědět vlastní cestu či port. Není to záruka
  nalezení libovolně přemístěného souboru nebo každé síťové služby.

Omezené, neúspěšné a neprozkoumané části kontroly zůstávají uvedené. Položka
v katalogu neznamená fyzické ověření všech jejích verzí a způsobů instalace.
Aplikace nekontroluje všechnu existující AI, neklasifikuje malware, nic
neblokuje a neprokazuje obsah přečtený či odeslaný jinou aplikací.

Výsledky lze uložit; podepsaný katalog lze ručně aktualizovat. Podporovaný
report můžete po náhledu a souhlasu dobrovolně odeslat. Firemní vzdálená
správa, mobilní platformy a síťové hledání jsou budoucí směry.
