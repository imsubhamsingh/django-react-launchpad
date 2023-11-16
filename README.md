# Django-React-Launchpad

Django-React-Launchpad is a powerful and efficient SaaS starter boilerplate that combines the robustness of Django as a backend framework with the flexibility of React for frontend development. This boilerplate is designed to kickstart your next SaaS project, saving you time and effort by providing a solid foundation and best practices.

## Features

- Django 4.x backend
- React 17.x frontend
- Webpack for bundling and optimization
- Pre-configured virtual environment using Poetry
- Easy setup and deployment
- Scalable architecture

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.10+
- Node.js 12.x or higher
- npm 6.x or higher
- virtualenv or Poetry

## Getting Started

To get started with Django-React-Launchpad, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/imsubhamsingh/django-react-launchpad.git
cd django-react-launchpad
```

2. Set up the frontend:

```bash
# Enter frontend project folder
cd frontend

# Install dependencies
npm install

# Run Webpack
npm run dev
```

3. Set up the backend:

```bash
# Enter Django project folder
cd backend

# Setup and activate virtualenv
poetry shell 

# Install requirements
poetry install

# Setup Django
./manage.py migrate
./manage.py runserver

# Then visit http://localhost:8000
```

Now you're ready to start building your amazing SaaS application!

## Contributing

We welcome contributions to improve and expand this boilerplate. If you'd like to contribute, please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License.
