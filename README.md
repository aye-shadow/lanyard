before running any of this, make sure you have node, jdk, and maven installed.

to run the frontend:
```bash 
cd frontend
cp .env.example .env.local
```
edit your newly created .env.local file with the required env variables
```bash
npm install
npm run dev
```
your frontend will be running on:
```bash
http://localhost:3000/
```

to run the backend:
```bash
cd backend
mvn spring-boot:run
```
your backend calls will be routed to:
```bash
http://localhost:8080/
```
