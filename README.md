cars = ["01 A 123 BC", "30 B 456 DE", "01 C 789 FG"]

def list_cars():
    for i, c in enumerate(cars, 1):
        print(f"{i}. {c}")

if __name__ == "__main__":
    list_cars()

$ git add app.py
$ git commit -m "feat: avtoturargohdagi mashinalar ro'yxatini chiqarish"
$ git log --oneline
d4e5f6a feat: avtoturargohdagi mashinalar ro'yxatini chiqarish
a1b2c3d chore: loyiha tuzilmasi yaratildi
