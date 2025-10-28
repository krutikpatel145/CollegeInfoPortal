
# 🎓 College Information Portal

## 📘 Project Title
**College Information Portal**

---

## 🧾 Description
The **College Information Portal** is a web application built using **ASP.NET Core MVC**.  
It allows administrators and staff to manage college-related information such as departments, courses, faculty, students, and events.  
This project demonstrates CRUD operations, form validation, and data management using **Entity Framework Core** and **Razor Views**.

Developed as part of the **Web Technologies with .NET** course, it showcases:
- MVC architecture  
- Model binding and validation  
- Database integration  
- Sessions and TempData  
- Layouts and partial views  

---

## ⚙️ Prerequisites
- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) (required)  
- (Optional) [Git](https://git-scm.com/downloads) — for cloning the repository  
- A code editor such as **Visual Studio 2022** or **Visual Studio Code**

> On the first run, the app automatically creates a local SQLite database file named **college.db** and seeds example data.  
> (See `Data/DbSeeder.cs` and `context.Database.EnsureCreated()` in `Program.cs`.)

---

## 📦 Installation Steps

1. **Download or Clone the Repository**
   - For developers:
     ```bash
     git clone https://github.com/yourusername/CollegeInfoPortal.git
     ```
   - For non-developers:
     - Click **Code → Download ZIP**
     - Extract it to your computer

2. **Open the Project**
   - In **Visual Studio Code**: open the folder and install the C# extension  
   - In **Visual Studio 2022**: open `CollegeInfoPortal.sln` and press **F5** to run

3. **Restore Dependencies**
   ```bash
   dotnet restore
````

4. **Build the Project**

   ```bash
   dotnet build
   ```

---

## 🚀 How to Run the Project

1. Run the app:

   ```bash
   dotnet run
   ```
2. Open your browser and go to:

   ```
   https://localhost:5001
   ```
3. The homepage of the **College Information Portal** will appear.
   The database will be automatically created and populated with sample data.

---

## 🌐 API Endpoint (Optional Feature)

A sample **Courses API** is available at:

```
/api/courses
```

You can test it with:

```bash
curl https://localhost:5001/api/courses
```

---

## 🧠 Technologies Used

* ASP.NET Core MVC (C#)
* Entity Framework Core (Code First)
* Razor Views
* Bootstrap 5
* SQLite / MySQL (for persistence)
* Visual Studio Code or Visual Studio 2022

