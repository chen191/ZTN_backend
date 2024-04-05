clone项目之后进行项目模块的拉取：
pip install PyMySQL
pip install daphne
pip install django-cors-headers
pip install channels
  
数据库迁移指令：  
python manage.py makemigrations  
python manage.py migrate  
python manage.py makemigrations sdpmanager_backend
python manage.py  sdpmanager_backend


项目执行命令：
python manage.py runserver

