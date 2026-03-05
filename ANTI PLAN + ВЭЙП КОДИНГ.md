# Уязвимый драйвер
[https://www.unknowncheats.me/forum/anti-cheat-bypass/739520-p2cs-vulnerable-driver.html]

# Важно прямо сейчас
- Дрочить cpp; assembly

## Мы можем уже сейчас
- Загрузить свой полноценный (неподписанный) драйвер-спуфер в память, обходя проверку подписей (DSE).
- **Direct Kernel Object Manipulation (DKOM)**: Напрямую менять структуры данных в памяти ядра.

## Нужно
Нужно очистить записи в таблицах `MmUnloadedDrivers` и `PiDDBCacheTable` , иначе античит поймет, что вы загружали «черный» драйвер для эксплуатации.

