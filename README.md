C:\Users\Estal\PycharmProjects\ONNX_bot\.venv\Scripts\python.exe C:\Users\Estal\PycharmProjects\ONNX_bot\py\clean_ticks.py 
[2025-05-29 20:42:01.164779] Очистка и проверка Ticks файла

Обработка файла: XAUUSD_Ticks_2024.01.01_2025.05.25.csv
Количество строк до очистки: 83610923
Количество строк после очистки: 83610923
Сохранен файл: C:\Users\Estal\PycharmProjects\ONNX_bot\csv\jforex\data_reworked\XAUUSD_Ticks_2024.01.01_2025.05.25_cleaned.csv

Проверка очищенного файла: C:\Users\Estal\PycharmProjects\ONNX_bot\csv\jforex\data_reworked\XAUUSD_Ticks_2024.01.01_2025.05.25_cleaned.csv
Столбцы в очищенном файле: ['Time (EET)', 'Ask', 'Bid', 'AskVolume', 'BidVolume']
Столбец Ask: тип данных корректен (числовой)
Столбец Bid: тип данных корректен (числовой)
Столбец AskVolume: тип данных корректен (числовой)
Столбец BidVolume: тип данных корректен (числовой)
Отрицательные/нулевые значения в Ask: 0
Отрицательные/нулевые значения в Bid: 0
Отрицательные/нулевые значения в AskVolume: 0
Отрицательные/нулевые значения в BidVolume: 0
Некорректный спред (Ask - Bid <= 0): 0
Нарушений монотонности времени: 0

Проверка завершена

Process finished with exit code 0

C:\Users\Estal\PycharmProjects\ONNX_bot\.venv\Scripts\python.exe C:\Users\Estal\PycharmProjects\ONNX_bot\py\check_15min_gaps.py 
[2025-05-29 21:37:41.641321] Проверка пропусков в 15 Mins файлах

Обработка файла: XAUUSD_15 Mins_Ask_2020.01.01_2025.05.25.csv
Пропуски во времени (больше ожидаемого интервала 0:15:00): 1391
Процент пропусков: 1.09%

Обработка файла: XAUUSD_15 Mins_Bid_2020.01.01_2025.05.25.csv
Пропуски во времени (больше ожидаемого интервала 0:15:00): 1391
Процент пропусков: 1.09%

Проверка завершена

Process finished with exit code 0

