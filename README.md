import datetime

# دالة لحساب البصمة الكربونية بناءً على تاريخ الولادة والوفاة
def calculate_carbon_footprint(birth_date, death_date, energy_consumption):
    # حساب عدد الأيام بين تاريخ الولادة والوفاة
    life_span = (death_date - birth_date).days
    # تقدير البصمة الكربونية بناءً على استهلاك الطاقة ومدة الحياة
    carbon_footprint = life_span * energy_consumption
    return carbon_footprint

# دالة لتقديم توصيات لتقليل البصمة الكربونية
def provide_recommendations(carbon_footprint):
    recommendations = []
    # إضافة توصيات بناءً على البصمة الكربونية
    if carbon_footprint > 10000:
        recommendations.append("التقليل من استخدام السيارات الخاصة.")
    if carbon_footprint > 5000:
        recommendations.append("زراعة الأشجار لتعويض الانبعاثات.")
    # يمكن إضافة المزيد من التوصيات هنا
    return recommendations

# مثال على استخدام الدوال
birth_date = datetime.date(1990, 1, 1)
death_date = datetime.date(2070, 1, 1)
energy_consumption = 0.5 # استهلاك الطاقة اليومي بالكيلوغرام

# حساب البصمة الكربونية
carbon_footprint = calculate_carbon_footprint(birth_date, death_date, energy_consumption)
print(f"البصمة الكربونية: {carbon_footprint} كيلوغرام")

# الحصول على التوصيات
recommendations = provide_recommendations(carbon_footprint)
print("التوصيات لتقليل البصمة الكربونية:")
for recommendation in recommendations:
    print(recommendation) 👋 Hi, I’m @OceanCollege
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
OceanCollege/OceanCollege is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
