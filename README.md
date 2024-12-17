## תנאים מוקדמים
- התקינו את [VS Code](https://code.visualstudio.com/download)
- התקינו את [NET Framework.](https://dotnet.microsoft.com/en-us/download)
- התקינו TypeScript בעזרת הרצת הפקודות:
```
powershell -c "irm bun.sh/install.ps1 | iex"
bun add -g typescript
```
- תנו לתוכנה גישה לפורט הרצוי (במקרה שלנו, פורט 5000) בעזרת פתיחת שורת המשימות כמנהל והרצת הפקודה:
```
netsh http add urlacl url=http://*:5000/ user=Everyone
```
## יצירת פרוייקט חדש
- בחלק העליון של העמוד, לחצו על הכפתור הירוק עליו כתוב "Use this template" ואז על "Create a new Repository", בחרו שם לפרוייקט ולחצו "Create repository".
- נשבט את הפרוייקט החדש שיצרנו בכך שנעתיק את כתובת האתר שלו, נפתח את ה-Command Pallate ב-VS Code, נבחר באפשרות "git: Clone" ונדביק את הכתובת שהעתקנו.

## הרצת הפרוייקט
נפתח את תיקיית הפרוייקט ב-VS Code ונריץ את הפרוייקט בעזרת הפקודה:
```
dotnet run
```
## מערכת יצירת משתמש \ התחברות למשתמש
![user_system](https://github.com/user-attachments/assets/6ec4c932-cf9c-470b-9d20-6e6c4254de33)
