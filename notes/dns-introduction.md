#DNS Basics (Domain Name System)

Co to jest DNS?
DNS zamienia nazwę domeny (np. google.com) na adres IP (np. 142.250.x.x), którego używa komputer do połączenia ze stroną.

---

## Jak działa DNS (kolejność zapytania)

1. **Hosts file**
   - lokalne ręczne przypisania domen → IP

2. **DNS cache**
   - zapisane wcześniej odpowiedzi

3. **Recursive DNS server**
   - pierwszy serwer DNS, który pyta komputer
   - sam wykonuje dalsze zapytania

4. **Root DNS server**
   - wskazuje serwery TLD

5. **Top-Level Domain (TLD) server**
   - obsługuje końcówki domen:
     - .com
     - .pl
     - .co.uk

6. **Authoritative DNS server**
   - zawiera prawdziwy adres IP domeny

---

##  Hosts file
- lokalny plik systemowy
- może nadpisywać DNS
- ma najwyższy priorytet

---

## TTL (Time To Live)
- czas ważności rekordu DNS
- liczony w sekundach

Przykład:
- 24h = 86400 sekund

---

## Narzędzia DNS

### nslookup
Szybkie sprawdzenie IP domeny:
```bash
nslookup google.com
