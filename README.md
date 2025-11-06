# README.md – Frontend Blog-Post 
**Project Name:** `frontend-blog`  
**Scope:** Pure Frontend (HTML + CSS + Bootstrap 5.3.3 )  
**Purpose:** Connect & consume backend API collection (Profile → Category → Article → Thumbnail)  
**Team:** NumberOne
**No backend code, no database, no Node.js**

```bash
# QUICK START (Copy-Paste តែ ៣ ឃ្លា)
git clone https://github.com/your-team/frontend-blog.git
cd frontend-blog
code . && live-server .   # បើមាន VS Code + Live Server


```text
frontend-blog/
├── index.html               # Login page
├── dashboard.html           # Main dashboard + sidebar
├── pages/                   # ទុក HTML ផ្នែកផ្សេងៗ
│   ├── profile.html
│   ├── categories.html
│   ├── articles.html
│   └── thumbnail.html
├── assets/
│   ├── css/
│   │   └── style.css        # Custom BS5 override
│   ├── js/
│   │   ├── main.js          # API URL + token + global
│   │   ├── profile.js       # POST avatar, GET profile, etc.
│   │   ├── category.js      # CRUD category
│   │   ├── article.js       # CRUD article + thumbnail
│   │   └── thumbnail.js     # Upload & delete thumbnail
│   ├── img/                 # placeholder images
│   └── vendor/
│       └── bootstrap/       # BS5 local (offline OK)
│           ├── css/bootstrap.min.css
│           └── js/bootstrap.bundle.min.js
├── partials/                # បំបែក code ដូចគ្នា
│   ├── navbar.html
│   ├── sidebar.html
│   └── footer.html
├── uploads/                 # Preview file មុន upload (git ignore)
├── .gitignore
└── README.md                # ឯកសារ នេះ


