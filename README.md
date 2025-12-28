# Django 博客系统

基于 Django 6.0 的完整博客平台，包含用户认证、文章管理和权限控制。

## 功能特性
- 用户注册、登录、退出
- 文章的创建、编辑、查看、删除
- 权限控制（仅作者可编辑）
- 响应式设计（Bootstrap 5.1）

## 技术栈
- Django 6.0
- Bootstrap 5.1
- SQLite 3
- Python 3.8+

## 快速开始
```bash
git clone https://github.com/[USERNAME]/django-blog-system
cd django-blog-system
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
pip install django
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
