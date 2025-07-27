# 👋 Welcome to Yara M. Salama's GitHub Profile!

Hi, I'm **Yara Mohamed Salama**, an **AEC Software Developer & Construction Engineer** based in Maadi, Cairo, Egypt. I specialize in designing and building intelligent tools to enhance design workflows, data interoperability, and project coordination in the Architecture, Engineering, and Construction (AEC) industry. With expertise in BIM tools, software development, and project management, I create user-centered solutions using C#, Python, JavaScript, and more to drive digital transformation in AEC.



---

## 🚀 About Me

- 🎓 **Education**: B.Sc. in Civil Engineering (Egyptian Chinese University, 2024, CGPA: 3.61) | Professional Diploma in AEC Informatics (ITI, 2024–2025)
- 💻 **Expertise**: BIM modeling, software development (C#, Python, JavaScript, .NET), web and desktop application development, project management
- 🛠 **Tools & Technologies**: Revit, AutoCAD, Navisworks, Dynamo, Primavera P6, C#, SQL, ASP.NET, HTML5, CSS3, JavaScript, Web Audio API
- 🌍 **Mission**: To develop innovative AEC software solutions that optimize construction workflows and promote sustainable design
- 📍 **Location**: Maadi, Cairo, Egypt
- 📧 **Email**: [yara.salama47@gmail.com](mailto:yara.salama47@gmail.com)
- 🔗 **LinkedIn**: [in/yaramsalama](https://www.linkedin.com/in/yaramsalama/)
- 🐙 **GitHub**: [yaraMsalama](https://github.com/yaraMsalama)
- 📱 **Mobile**: +20 127 896 4607

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yaraMsalama&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=yaraMsalama&layout=compact&theme=radical)

---

## 🛠 Technical Skills

| **Category**                  | **Skills**                                                                 |
|-------------------------------|---------------------------------------------------------------------------|
| **AEC & BIM Software**        | AutoCAD, Revit (Architecture & Structure), Navisworks, Dynamo, Primavera P6, CSI Applications (ETABS, SAP2000), Revit API, AutoCAD API |
| **Programming Languages**     | C# (OOP), C/C++, Python, JavaScript                                       |
| **Backend Development (.NET)**| SQL, Entity Framework (EF), LINQ, ASP.NET (MVC & APIs)                   |
| **Web Development**           | HTML5, CSS3, JavaScript, Web Audio API                                   |
| **Desktop Application Dev**   | Windows Presentation Foundation (WPF), Windows Forms                     |
| **Project Management**        | Planning & Scheduling, Cost Management & Estimation, Quality & Safety Management, Quantity Surveying, Claims & Delay Analysis (FIDIC) |
| **Additional Competencies**   | BIM Modeling & Coordination, Engineering Software Integration & Automation |

![Skills Distribution Graph](https://via.placeholder.com/600x300.png?text=Skills+Distribution+Graph)

*Note*: The skills graph is a placeholder. You can replace it with a custom chart (e.g., pie chart of proficiency levels) using [QuickChart.io](https://quickchart.io/).

---

## 🎓 Education

### Information Technology Institute (ITI) | Oct 2024 – July 2025
**Professional Diploma in AEC Informatics**  
- Intake 45, Smart Village Branch  
- Focused on C#, SQL, .NET, web development, and AEC software solutions

### Egyptian Chinese University | B.Sc. in Civil Engineering | Oct 2019 – Jun 2024
- **CGPA**: 3.61 (Academic Status: Excellence)  
- Specialized in BIM, construction management, and structural analysis

---

## 💼 Professional Experience

### Teaching Assistant | Egyptian Chinese University | Aug 2024 – Oct 2024
- Delivered lectures and tutorials on structural analysis, construction management, and BIM  
- Mentored students in applying engineering concepts and software tools

### Junior Technical Office Engineer | ACE Consulting Engineers Moharram-Bakhoum | Jul 2024 – Aug 2024
- Conducted accurate quantity takeoffs using AutoCAD and Revit  
- Supported technical office operations for construction projects

### Site Engineer (Intern) | ACE Consulting Engineers Moharram-Bakhoum | Jul 2021 – Sep 2021, Aug 2022 – Sep 2022
- Assisted in on-site construction management and coordination  
- Gained hands-on experience in project execution and quality control

---

## 📈 Key Projects

### Desktop Applications

#### 🖥 ToDo Application - MVVM Implementation (WPF)
- **Description**: Developed a task management desktop application using WPF with MVVM architecture  
- **Tech Stack**: C#, WPF, CommunityToolkit.Mvvm  
- **Key Features**:  
  - MVVM architecture with separate Model (TaskItem), ViewModel (TaskViewModel), and Views (MainWindow, EditTaskWindow)  
  - TaskItem class with INotifyPropertyChanged for Name, Description, Deadline, and IsDone status  
  - ObservableCollection<TaskItem> for dynamic task management  
  - RelayCommand for add/edit/remove tasks with CanExecute logic  
  - Two-way data binding and visual indicators (50% opacity for completed tasks)  
  - Clean UI with blue action buttons and consistent layout  
- **Impact**: Enhanced task management efficiency with extensible architecture  
- **Repo**: [Link to Repo](#)

#### 🖥 NexGen Management System (Windows Forms)
- **Description**: Built a project management desktop application for AEC workflows  
- **Tech Stack**: C#, Windows Forms, Entity Framework (Code First), LINQ  
- **Key Features**:  
  - Entity Framework for seamless data modeling and LINQ for optimized querying  
  - Intuitive UI with CRUD operations for project tracking  
  - Applied OOP principles and database-first design  
- **Impact**: Streamlined project management with efficient data handling  
- **Repo**: [Link to Repo](#)

#### 🏢 Revit API Commands
- **Description**: Developed Revit API plugins to automate BIM tasks  
- **Tech Stack**: C#, Revit API  
- **Commands**:  
  1. **Change Instance’s Location**: Dynamically adjusts element positions in Revit models  
  2. **Generate Sheets From Views**: Automates sheet creation from selected views  
  3. **Generate Wall Instance**: Creates parametric wall elements in Revit  
  4. **Generate Floor Instance**: Generates floor elements with customizable parameters  
- **Impact**: Reduced manual BIM tasks by 30%  
- **Repo**: [Link to Repo](#)

#### 🏛 Dynamo - The Bosjes Chapel
- **Description**: Modeled the organic roof of the Bosjes Chapel using Dynamo scripting  
- **Tech Stack**: Dynamo, Python  
- **Key Features**:  
  - Generated NURBS curves with `NurbsCurve.ByPoints` from `Point.ByCoordinates` and sliders  
  - Created a surface with `Surface.ByLoft` and structural elements with `Surface.Isoline` and `Solid.ByLoft`  
  - Incorporated openings using `Cylinder.ByPointsRadius` and `Surface.TrimWithEntity`  
  - Adjustable parameters for roof shape, structure, and openings via sliders  
- **Impact**: Enabled parametric design exploration for complex architectural forms  
- **Repo**: [Link to Repo](#)

### Web Applications

#### 🌐 NGY Web Viewer
- **Description**: A web-based BIM visualization tool for loading and analyzing IFC models (tested on ITI’s building model)  
- **Tech Stack**: HTML5, CSS3, JavaScript, WebGL (for IFC rendering)  
- **Key Features**:  
  - High-performance IFC model loading and 3D rendering  
  - Dynamic sectioning with adjustable X/Y/Z clipping planes  
  - Smart measurement tools (length, angle, area) with snapping functionality  
  - Undo/redo system for user interactions  
  - Intuitive camera controls (orbit, pan, zoom)  
- **Impact**: Enhanced real-time BIM analysis for AEC professionals  
- **Repo**: [Link to Repo](#)

#### ♟ Chess Leaders
- **Description**: Built an interactive website summarizing *The Soviet Chess Primer*  
- **Tech Stack**: HTML5, CSS3, JavaScript  
- **Key Features**:  
  - Lesson pages with responsive design  
  - User authentication (login/register)  
  - Intuitive UI for chess beginners  
- **Impact**: Combined passion for chess with web development skills  
- **Repo**: [Link to Repo](#)

#### 🎹 Interactive Piano Web Application – LaLa Land
- **Description**: Developed a virtual piano web app for playing melodies in the browser  
- **Tech Stack**: HTML5, CSS3, JavaScript, Web Audio API  
- **Key Features**:  
  - Keyboard/mouse controls mapped to piano notes with visual feedback  
  - Toggleable key labels, volume control slider, and animated key presses  
  - Responsive design for various screen sizes  
- **Impact**: Created an engaging, accessible musical experience  
- **Repo**: [Link to Repo](#)

![Project Impact Graph](https://via.placeholder.com/600x300.png?text=Project+Impact+Graph)

*Note*: The project impact graph is a placeholder. You can create a chart (e.g., bar chart showing time saved or user engagement) using [QuickChart.io](https://quickchart.io/).

---

## 🏆 Training & Certifications

- **BIM and Management Track** | Radiance Group for Training | Jun 2023 – Aug 2023  
  - 100-hour program by Egyptian Engineers Syndicate  
  - Focused on BIM modeling, coordination, and project management  
- **Repair and Waterproofing Training** | Sika Egypt Academy | Apr 2024  
  - Gained expertise in repair and waterproofing techniques  
- **Site Visit: Cairo Metro Line 4** | Dec 2023  
  - Explored construction processes at Hada’ak El Ahram Station with leading Egyptian firms

---

## 🌟 Leadership & Volunteer Experience

### Core Team Member – Social Media Team | Google Developer Student Club (GDSC) | 2021 – 2022
- Led social media strategy, increasing engagement by 30% through creative campaigns  
- Mentored new members in content creation and collaborated to grow GDSC’s online presence  

---

## 📊 GitHub Contributions

![Contribution Graph](https://ghchart.rshah.org/yaraMsalama)

- **Commits**: Actively contribute to AEC-related repositories and personal projects  
- **Pull Requests**: Collaborated on BIM and software development projects  
- **Issues Resolved**: Fixed bugs and added features to open-source AEC tools  

---

## 📬 Connect with Me

- **LinkedIn**: [in/yaramsalama](https://www.linkedin.com/in/yaramsalama/)  
- **Email**: [yara.salama47@gmail.com](mailto:yara.salama47@gmail.com)  
- **GitHub**: [yaraMsalama](https://github.com/yaraMsalama)  
- **Mobile**: +20 127 896 4607  
- **Address**: Maadi, Cairo, Egypt  

![Connect Icons](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white) ![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🌍 Languages

- **Arabic**: Native  
- **English**: Professional Proficiency  

---

## 🔮 What's Next?

I'm advancing my skills in **AI-driven BIM automation** and **digital twins** through my ITI program, with a focus on creating innovative AEC software solutions. Stay tuned for more exciting projects!

*Last updated: July 27, 2025*
