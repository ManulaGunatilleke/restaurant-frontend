### Resturent System

Technology Stacks and used for the System 
 -  Java Script(Language)
 -  React Library 
 -  Tailwind CSS
 -  Container(Docker)

## Set up the project 

### 1. Clone the repository:

``` bash
git clone https://github.com/ManulaGunatilleke/restaurant-frontend.git
```

### 2. Frontend navigation:

- Go to inside restaurant-frontend folder
  
``` bash
cd restaurant-frontend 
```

### 3. Install dependencies for frontend:

``` bash
npm init
```
-Note -: install required libraries by using "npm i {Name of the Library}"

### 4. Build Dockerfile for frontend:

``` bash
docker build -t restaurant-frontend .
```
-Note -: You need to install Docker to your Device based on the OS

### Link -: https://docs.docker.com/desktop/

### 5. Start backend:

- Go to inside restaurant-service folder
  
``` bash
npm start (Option 1)
docker run -d -p 3000:3000 restaurant-frontend or start using Docker Desktop (Option 2) 
```
### Full Code -: https://github.com/ManulaGunatilleke/resturent-all.git
