# student-management-system-deploy# Student Management System - Deployment Guide

## Pull images

```bash
docker pull nhan295/student-management-system-backend
docker pull nhan295/student-management-system-frontend
docker pull nhan295/student-management-system-mysql
```

## Run using Docker Compose
```bash
git clone https://github.com/ban-ten/student-management-system-deploy.git
cd student-management-system-deploy
docker-compose up -d
```

