# README.md – Frontend Blog-Post 
**Project Name:** `frontend-blog`  
**Scope:** Pure Frontend (HTML + CSS + Bootstrap 5.3.3 )  
**Purpose:** Connect & consume backend API collection (Profile → Category → Article → Thumbnail)  
**Team:** NumberOne
**No backend code, no database, no Node.js**



## Folder Structure – ត្រូវតែ Follow 100% (ហាមកែផ្លាស់!)

**Copy រចនាសម្ព័ន្ធ នេះ ទុកក្នុង `README.md` របស់អ្នកភ្លាម!**

```text
frontend-blog/                  ← ឈ្មោះ folder ឫ project
├── index.html                  # ទំព័រ Login (ហាមលុប!)
├── dashboard.html              # ទំព័រ Dashboard + Sidebar
├── pages/                      # ទុក HTML ផ្នែកផ្សេងៗ (កុំដាក់ក្នុង root)
│   ├── profile.html            # Profile + Upload avatar
│   ├── categories.html         # CRUD Category
│   ├── articles.html           # CRUD Article
│   └── thumbnail.html          # Upload/Delete thumbnail
├── assets/
│   ├── css/
│   │   └── style.css           # Custom BS5 តែមួយ file
│   ├── js/
│   │   ├── main.js             # API URL + token + global function
│   │   ├── profile.js          # ទាំងអស់ /api/profile
│   │   ├── category.js         # ទាំងអស់ /api/category
│   │   ├── article.js          # ទាំងអស់ /api/article
│   │   └── thumbnail.js        # Upload & delete thumbnail
│   ├── img/                    # Placeholder រូបភាព
│   └── vendor/
│       └── bootstrap/          # BS5 local (offline OK)
│           ├── css/bootstrap.min.css
│           └── js/bootstrap.bundle.min.js
├── partials/                   # បំបែក code ដូចគ្នា
│   ├── navbar.html
│   ├── sidebar.html
│   └── footer.html
├── uploads/                    # Preview file មុន upload → git ignore!
├── .gitignore                  # មាន rule /uploads/ រួចហើយ
└── README.md                   # ឯកសារ នេះត្រូវ update ជានិច្ច

