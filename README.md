# Анализатор пакетов (снифер)

![Python-3.9.7](https://img.shields.io/badge/Python-v3.9.7-blue?style=for-the-badge) 


Для корректной работы программы требуются следующие библиотеки:
```python
from struct import pack
import scapy.all as scapy
from scapy.layers import http
```

Результатом данной программы является анализ пакетов или вывод логина и пароля при авторизации:

![image](https://user-images.githubusercontent.com/131512468/236254684-4821131b-741d-4694-939a-e8efb98a9a18.png)

![image](https://user-images.githubusercontent.com/131512468/236254823-ab2137da-6e28-461e-a86e-13227b663e77.png)
