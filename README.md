# 📝 Django Blog Website

A simple **Blog Application** built with Django where users can view a list of blog posts and read full details by clicking on the title. Posts can also be managed via the Django admin panel.  

---

## 🚀 Features
- View all blog posts on the homepage  
- Click a post title to read the full content  
- Admin panel to create, edit, and delete posts  
- Base template for consistent design  
- Clean and responsive UI  

---

## 📂 Project Structure
Blog-website/
│── blog/                # Main project (settings, urls, wsgi, asgi)
│── posts/               # Blog app
│   │── models.py        # Post model (title, content, created_at)
│   │── views.py         # Views for list & detail pages
│   │── urls.py          # App-level routes
│   │── templates/posts/ # HTML templates (base, list, detail)
│── manage.py            # Django management script
│── venv/                # Virtual environment (not pushed to GitHub)

---

## ⚡ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/blog-website.git
cd blog-website

2. Create & activate virtual environment
python3 -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

3. Install dependencies
pip install -r requirements.txt

4. Apply database migrations
python manage.py migrate

5. Create superuser (for admin panel)
python manage.py createsuperuser

6. Run the server
python manage.py runserver

Now open your browser:
	•	Homepage → http://127.0.0.1:8000/
	•	Admin Panel → http://127.0.0.1:8000/admin/
