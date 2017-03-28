# docker-platform-tester

wait-for-it.sh https://github.com/vishnubob/wait-for-it

### Required Modules and Infrastructure
- [x] Django  
- [x] Docker-compose  
- [x] Mysql  
- [x] Gunicorn  
- [ ] Mysql persistent data volume connection
- [ ] AWS EB config (public deployment)

### Required startup actions
- [ ] python manage.py collectstatic
- [ ] python manage.py makemigrations
- [ ] python manage.py migrate
