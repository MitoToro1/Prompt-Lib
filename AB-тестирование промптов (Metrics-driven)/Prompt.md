A/B тест двух промптов для генерации SQL:

Prompt A: "Напиши SQL SELECT для таблицы users WHERE age > 25"
Prompt B: "Сгенерируй SQL query. Schema: users(id, name, age). Filter: age>25. Explain reasoning."

Оцени по критериям:
1. Корректность SQL (да/нет)
2. BLEU score vs reference
3. Human readability (1-5)
4. Latency (токены/сек)

Рекомендация: какой промпт выбрать для production?