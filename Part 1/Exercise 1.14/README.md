sudo docker build -t e-backend .
sudo docker run -p 8080:8080 e-backend

sudo docker build -t e-frontend .
sudo docker run -p 5000:5000 e-frontend

