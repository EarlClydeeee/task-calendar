# task-calendar
This project is a lightweight, interactive scheduler web application designed to help users plan and manage their tasks efficiently.

scheduler-system
│
├── /app/                # Core logic modules (AI, API handlers, etc.)
│   ├── scheduler/       # Scheduling logic, rules, constraints
│   ├── ai/              # Python-based AI engine and prediction models
│   └── api/             # PHP-based APIs to handle requests and DB access
│
├── /client/             # React application and UI components
│   ├── components/      # Reusable UI parts (Calendar, TaskCard, Modals)
│   ├── pages/           # Main views/screens
│   ├── assets/          # Images, logos, icons
│   └── utils/           # Helper functions, constants
│
├── /config/             # Environment settings, CORS config, API routes
│   ├── database.php     # DB connection setup
│   ├── routes.php       # Endpoint mappings
│   └── ai_config.py     # Python AI settings
│
├── /scripts/            # CLI tools, data seeding, maintenance scripts
│   ├── seed_tasks.php
│   └── train_model.py
│
├── /public/             # Static files (index.html, manifest, etc.)
│   └── favicon.ico
│
├── /tests/              # Unit and integration tests
│   ├── php/
│   ├── js/
│   └── py/
│
├── /logs/               # Server logs, AI inference logs
│
├── /models/             # Trained AI models and saved data files
│   └── task_predictor.pkl
│
├── package.json         # React dependencies
├── composer.json        # PHP dependencies
├── requirements.txt     # Python dependencies
├── .env                 # Environment variables
├── README.md
└── docker-compose.yml   # (Optional) Dev containerization setup
