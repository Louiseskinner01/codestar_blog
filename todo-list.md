# Full Project To-Do Checklist

## A. Planning & Concept
- [ ] Define the project purpose
- [ ] Decide who the users are (user types)
- [ ] Identify user needs & motivation
- [ ] Write core user stories (As a user, I want…)
- [ ] Define the Minimum Viable Product (MVP)
- [ ] List stretch features (nice-to-have)
- [ ] Write a short project description / vision
- [ ] Create wireframes (basic sketches)
- [ ] Create a Trello board (optional but recommended)

## B. Project Setup (Local Machine)
- [ ] Create project folder in VS Code
- [ ] Create a GitHub repo
- [ ] Add README.md with project description
- [ ] Initialise git in your folder
- [ ] Connect local project to GitHub repo
- [ ] Install Python 3.12
- [ ] Create a virtual environment (venv)
- [ ] Activate the venv
- [ ] Install Django inside venv
- [ ] Create a requirements.txt file
- [ ] Run Django server to verify installation

## C. Django Project Structure
- [ ] Create Django project (django-admin startproject)
- [ ] Create main application (e.g., core app)
- [ ] Create additional apps (accounts, blog, etc.)
- [ ] Add apps to INSTALLED_APPS
- [ ] Configure settings.py (templates, static files)
- [ ] Create the base folder structure (templates/, static/, media/)
- [ ] Set up environment variables (.env)

## D. Database & Models
- [ ] Choose database (PostgreSQL for deployment)
- [ ] Create an ERD (entity relationship diagram)
- [ ] Draft all models for your app(s)
- [ ] Add model relationships (FKs, M2M, OneToOne)
- [ ] Run makemigrations / migrate
- [ ] Create superuser for admin panel
- [ ] Test models in Django admin

## E. URL Routing & Views
- [ ] Set up project-level urls.py
- [ ] Create app-level urls.py
- [ ] Create basic views
- [ ] Connect URLs → Views → Templates
- [ ] Test each route

## F. Templates & Frontend
- [ ] Create base.html with blocks
- [ ] Link CSS file(s)
- [ ] Build navigation bar & footer
- [ ] Build core page layouts (home, about, login, etc.)
- [ ] Add responsive design (Bootstrap, custom CSS, etc.)
- [ ] Add forms (HTML + Django forms)
- [ ] Test all templates render correctly

## G. User Accounts & Authentication
- [ ] Enable Django authentication system
- [ ] Create signup form
- [ ] Create login & logout views
- [ ] Add password hashing (Django does this automatically)
- [ ] Test authentication flow
- [ ] Protect pages with @login_required
- [ ] Add messages framework (success/error messages)
- [ ] Create user profile page (optional)

## H. App Logic / Main Features
- [ ] Implement MVP features
- [ ] Add CRUD functionality
- [ ] Add form validation
- [ ] Add pagination (if needed)
- [ ] Add search (optional)
- [ ] Add user permissions (if needed)
- [ ] Test functionality thoroughly

## I. Static & Media Files
- [ ] Set up static file handling
- [ ] Configure media file upload
- [ ] Test static + media in development

## J. Final Prep Before Deployment
- [ ] Freeze requirements.txt
- [ ] Remove unused files
- [ ] Update README with full documentation
- [ ] Prepare environment variables
- [ ] Test app in local production mode

## K. Deployment (Heroku or Render)
- [ ] Create Heroku/Render account
- [ ] Create new app project
- [ ] Add PostgreSQL database
- [ ] Add environment variables
- [ ] Push code to deployment platform
- [ ] Run migrations
- [ ] Collect static files
- [ ] Test deployed app

## L. After Deployment
- [ ] Test all features in production
- [ ] Fix any bugs found
- [ ] Update documentation
- [ ] Push final commit
- [ ] Mark project as complete 🎉
