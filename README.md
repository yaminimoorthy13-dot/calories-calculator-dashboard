* Calories Calculator — Health Dashboard*
A fully client-side health dashboard web app that helps users track daily calorie intake, calculate BMI, and monitor progress with interactive charts.

Built as part of the Web Development course at VIT Vellore.


Team Members

NameReg No:
Yamini M 24BCS0034
Mukesh GE 24BCS0029
Navanitha K 24BCS0033


 Features


🔐 Login / Logout — Email-based login with password visibility toggle (stored via localStorage)
📊 BMI Calculator — Calculates Body Mass Index from height and weight
🔥 BMR & Maintenance Calories — Uses the Mifflin-St Jeor formula based on age, height, weight, and gender
🍛 Indian Meal Selector — 20+ Indian food options across Breakfast, Lunch, Snacks, and Dinner with auto calorie calculation
📈 Chart.js Visualizations — Target vs Consumed bar chart + daily history line graph
🔥 Daily Streak Tracker — Tracks consecutive login days
🏆 Achievement Badges — Awarded for Healthy BMI and Calorie Controlled goals
💎 Glassmorphism UI — Modern frosted-glass design, fully responsive



 Screenshots

Login PageDashboardEmail & password login with toggleWelcome screen with personal details input

Meal SelectionResults & ChartsBreakfast, Lunch, Snacks, Dinner optionsBMI, Maintenance calories, Achievement badges


 Tech Stack


HTML — Page structure
CSS — Glassmorphism styling, responsive layout
JavaScript — Logic, calculations, interactivity
Chart.js — Bar chart and line graph visualizations
LocalStorage — Client-side data persistence (no backend required)



 Meal Options

MealOptionsBreakfast2 Idlis, 3 Dosa, Pongal, Oats 1 cupLunchVegetable Rice, Tomato Rice, Sambar Rice, Boiled Eggs, Cucumber, Carrot, ChickenSnacksPeanut, Tea, Fruits, Bread SlicesDinnerChapatti, Macaroni, Chicken Rice, Paneer


 Calculations Used

BMI:

BMI = weight (kg) / height (m)²

BMR (Mifflin-St Jeor Formula):

Male:   BMR = (10 × weight) + (6.25 × height) - (5 × age) + 5
Female: BMR = (10 × weight) + (6.25 × height) - (5 × age) - 161

Maintenance Calories:

Maintenance = BMR × 1.55 (moderate activity)


 How to Run

No installation needed! This is a fully client-side app.


Clone the repository:


bashgit clone https://github.com/yaminimoorthy13-dot/calories-calculator-dashboard.git


Open index.html in any browser
Enter any email and password to log in
Fill in your details and select meals to generate your report



 Project Structure

calories-calculator-dashboard/
│
├── index.html       # Main app (HTML + CSS + JS in one file)
└── README.md


 Limitations


Data is stored in browser localStorage (lost if cleared)
No real authentication (any email/password works)
Not accessible across different devices



 Future Work


Add real authentication (Firebase / Backend API)
Store data in cloud database
Add workout and water intake tracking
Personalized diet recommendations using AI
Mobile app version



License

This project was submitted as an academic course project at VIT Vellore. For educational use only.
