# TechBlog

A simple and clean blog application built with **Django**, designed to publish technical articles, tutorials, and personal insights.

---

## Table of Contents

- [About](#about)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Database Setup & Migrations](#database-setup--migrations)  
  - [Running the Project](#running-the-project)  
- [Usage](#usage)  
- [Folder Structure](#folder-structure)  
- [Contributing](#contributing)  
- [License](#license)  
- [Future Improvements](#future-improvements)  
- [Contact](#contact)  

---

## About

**TechBlog** is a Django-based blogging platform to manage and publish technical content. It enables users (or administrators) to write, edit, and delete blog posts, while providing a clean, minimal front-end for readers.

**Motivation**:  
- To build a simple, maintainable blog application using Django  
- To practice Django best practices (models, views, templates, admin)  
- To create a platform for writing and sharing technical articles  

**Use Cases**:  
- Developer’s personal blog  
- Technical documentation + blog hybrid  
- Learning project for Django novices  

---

## Features

- Create, edit, and delete blog posts  
- Rich text support (via Django admin)  
- List and detail views for blog posts  
- Responsive UI with clean, semantic HTML  
- Admin interface powered by Django Admin  
- Basic security with Django’s authentication (if extended)  
- Easily extensible for features such as tagging, comments, categories  

---

## Tech Stack

| Layer | Technology |
|---|---|
| Backend | Django (Python) |
| Frontend | HTML, CSS |
| Database | SQLite (default) / any Django-supported DB |
| Environment | Virtualenv or venv |

---

## Getting Started

Follow these instructions to run the project locally.

### Prerequisites

- Python 3.x installed  
- pip (Python package manager)  
- Virtual environment tool (`venv` / `virtualenv`)  

### Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/ak-127/techblog.git
   cd techblog
