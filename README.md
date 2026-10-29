# DataTrail

A Chrome extension that automatically notes where you have shared which **type** of personal information online, and helps you request deletion.

> B.Tech Major Project | Maharana Pratap Engineering College, Kanpur

## Key Features
- Detects form fields and classifies them (phone, email, name, address, password, other)
- Logs only the **category**, website and date. The typed value is **never** saved
- Risk level per site (High / Medium / Low)
- Delete Assistant: delete-account link, erasure email draft, request status tracking, 30-day reminder
- All data stays in the browser (local storage). No server.

## Tech Stack
- **Extension:** HTML, CSS, JavaScript, Manifest V3, content script, service worker, chrome.storage
- **ML:** Python, Pandas, Scikit-learn (TF-IDF + Logistic Regression), Jupyter/Colab

## Project Structure
```
DataTrail/
├── frontend/
│   └── index.html    # Project overview website
├── LICENSE
├── .gitignore
└── README.md
```

## Team
- Irfan Ahmad (Group Leader)
- Aryan Katiyar
- Ashray Agnihotri
- Pradyuman Yadav
- Osama Rais

**Guide:** Samarth Porwal

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
