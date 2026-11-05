# m – przekierowanie kodów QR / NFC maszyn

Naklejki na maszynach zawierają adres `https://gabrielskubis.github.io/m/?id=<ID maszyny>`.
Strona `index.html` przenosi do systemu ustawionego w linijce `var CEL=...`
(`appsscript`, `appsheet`, `aplikacja` albo `wybor` – ekran z przyciskami).
`404.html` to kopia, obsługuje też adresy w formie `/m/<ID>`.
Zmiana systemu = zmiana jednej linijki, naklejki zostają bez zmian.
