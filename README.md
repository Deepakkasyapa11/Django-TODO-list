# DJANGO Task Mangement App (Django-based)

A streamlined Task Management implementation focusing on **RESTful patterns** and **User Data Isolation**.

# Technical Highlights
- **Architecture:** Decoupled Logic using Django Class-Based Views (CBV).
- **Security:** Implemented `LoginRequiredMixin` for strict access control.
- **State Management:** Logic-driven task filtering (User-specific querysets).

# Setup & Installation
1. Clone the repository.
2. Initialize virtual environment: `python -m venv venv`.
3. Install dependencies: `pip install -r requirements.txt`.
4. Run Migrations: `python manage.py migrate`.
5. Start Server: `python manage.py runserver`.

# Future Roadmap
- [ ] Implement JWT for API-based interaction.
- [ ] Add Redis caching for task retrieval optimization.
