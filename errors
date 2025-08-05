age_in_months = []
answer = input("Którego roku się urodziłeś? ")
try:
  int(answer)
  year_of_birth = int(answer)
  if year_of_birth > 2025 or year_of_birth < 1875:
    raise ValueError("co ty jesteś trupem?")
  else:
    age = (2025 - year_of_birth) * 12
    age_in_months.append(age)
except TypeError:
  raise ValueError("brat nie zna swojego roku urodzenia")
month = input("Którego miesiąca się urodziłeś (słownie)? ")
if month in ["styczeń", "styczeń ", "styczen ", "styczen"]:
  age_in_months.append(6)
elif month in  ["luty ", "luty"]:
  age_in_months.append(5)
elif month in ["marzec", "marzec "]:
  age_in_months.append(4)
elif month in ["kwiecień", "kwiecień ", "kwiecien",  "kwiecien "]:
  age_in_months.append(3)
elif month in ["maj", "maj "]:
  age_in_months.append(2)
elif month in ["czerwiec", "czerwiec "]:
  age_in_months.append(1)
elif month in ["lipiec", "lipiec "]:
  age_in_months.append(0)
elif month in ["sierpień", "sierpień ", "sierpien", "sierpien "]:
  age_in_months.append(-1)
elif month in ["wrzesień", "wrzesień ", "wrzesien", "wrzesien "]:
  age_in_months.append(-2)
elif month in ["październik", "październik ", "pazdziernik", "pazdziernik "]:
  age_in_months.append(-3)
elif month in ["listopad", "listopad "]:
  age_in_months.append(-4)
elif month in ["grudzień", "grudzień ", "grudzien", "grudzien "]:
  age_in_months.append(-5)
else:
  raise ValueError("napisz poprawnie")
result = age_in_months[0] + age_in_months[1]
print("Masz " + 
result = age_in_months[0] + age_in_months[1]
print("Masz " + str(result) + " miesięcy")
