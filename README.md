# finance_2526
Finance management web app
Project File Tree:

finance-app/
│
├── app.py
├── config.py
├── requirements.txt
├── models.py
├── forms.py
├── routes.py
├── run.py
├── migrations/    # after you run flask-migrate (optional)
│
├── instance/
│   └── .env       # SECRET_KEY and UPLOAD_PATH if you want
│
├── uploads/       # file uploads saved here (create this folder)
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── audit_log.html
│   ├── reimbursement_form.html
│   ├── purchase_request.html
│   ├── grants.html
│   ├── grant_detail.html
│   ├── expenditures.html
│   ├── design_team.html
│   └── partials/... (optional)
│
└── static/
    ├── css/
    └── js/
        └── purchase_items.js
