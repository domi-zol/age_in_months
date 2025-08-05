age_in_months = []
year_of_birth = int(input("Którego roku się urodziłes? "))
age = (2025 - year_of_birth) * 12
age_in_months.append(age)
month = input("Którego miesiąca się urodziłeś? ")
if month in ["styczeń", "styczeń ",  "styczen "  "styczen"]:
  age_in_months.append(6)
elif month in ["luty ", "luty"]:
  age_in_months.append(5)
elif month in ["marzec", "marzec "]:
  age_in_months.append(4)
elif month in ["kwiecień",  "kwiecień ", "kwiecien", "kwiecien "]:
  age_in_months.append(3)
elif month in["maj", "maj "]:
  age_in_months.append(2)
elif month in ["czerwiec", "czerwiec "]:
  age_in_months.append(1)
elif month in ["lipiec", "lipiec "]:
  print("Sto lat")
elif month in ["sierpień", "sierpień ",  "sierpien", "sierpien "]:
  age_in_months.append(-1)
elif month in ["wrzesień", "wrzesień ", "wrzesien", "wrzesien "]:
  age_in_months.append(-2)
elif month in ["październik", "październik ", "pazdziernik", "pazdziernik "]:
  age_in_months.append(-3)
elif month in ["listopad", "listopad "]:
  age_in_months.append(-4)
elif month in ["grudzień", "grudzień ", "grudzien", "grudzien "]:
  age_in_months.append(-5)
result = sum(age_in_months)
print("Masz " + str(result) + " miesięcy")
