# Calculator Java

## Metrike

### LOC (Linije koda)

- Ukupan broj linija koda za ceo projekat: 104

### Ciklomatska složenost

- Metoda `evaluateExpression`: 5 grana/uslova
- Metoda `Calculate`: 8 grana/uslova

### Statička analiza

- Nisu pronađene izričite nedoslednosti ili propusti.

## Zapažanja

- Metoda `evaluateExpression` ima jasno definisan proces parsiranja izraza, ali bi bilo korisno dodati proveru na ulaznom izrazu kako bi se izbegle greške pri unosu neispravnog izraza.

- Metoda `Calculate` sadrži veliki broj uslova i grananja, što može otežati razumevanje i održavanje koda. Razmatranje refaktorisanja ove metode može poboljšati čitljivost i održivost.
