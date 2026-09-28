Provável estrutura do projeto:

ComexCost Pro
├── Backend:  Python + Django + Django REST Framework
├── Frontend: HTML5 + CSS3 + Bootstrap 5 + Chart.js
├── Database: PostgreSQL (produção) / SQLite (dev)
├── APIs externas:
│   ├── Banco Central PTAX (câmbio oficial)
│   ├── AwesomeAPI (câmbio comercial)
│   └── Receita Federal (consulta NCM/TIPI)
├── PDF:        ReportLab ou WeasyPrint
├── Auth:       Django Allauth (login simples)
├── Deploy:     Railway / Render / PythonAnywhere (free tier)
└── Versionamento: Git + GitHub (commit diário, README profissional)
