```Python
class Nikita:
    def __init__(self):
        self.name = "Никита"
        self.city = "г.Екатеринбург."
        self.job = "Снабженец by day, Python-разработчик by night"
        self.learning_platform = "Skypro"
        self.stack = ["Python", "Git"]
        self.hobbies = ["Тюнинг Matiz'а", "Автоматизация рутины", "Поиск себя в IT"]
        self.dreams = ["Удалёнка", "Двое детей", "Собака", "Дом с гаражом", "Здоровые родные"]

    def current_status(self):
        return "Учусь. Копаюсь. Пишу код. Иногда сплю."

    def say_hello(self):
        print(f"\n👋 Привет, я {self.name} из {self.city}")
        print("Учусь работе на Python. Пока что ошибок больше, чем строк кода. Но это временно. 💪\n")

    def daily_routine(self):
        routine = {
            "09:00–18:00": "Работаю там, где не хочется.",
            "18:00–23:00": "Учусь писать код, чтобы работать там, где хочется.",
            "23:01": random.choice([
                "Падаю спать.",
                "Гуглю 'python как заставить работать код'.",
                "Пытаюсь понять почему ничего не работает."
            ])
        }
        print("📅 Мой день:")
        for time, activity in routine.items():
            print(f"  {time}: {activity}")
        print()

    def future_plan(self):
        print("🔮 Планы на будущее:")
        print("Перейти в IT и кайфовать от каждого коммита 🚀\n")

if __name__ == "__main__":
    me = Nikita()
    me.say_hello()
    print("🛠 Текущий статус:", me.current_status(), "\n")
    me.daily_routine()
    me.future_plan()
```
