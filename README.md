# ChamalHat - School Management

## Getting Started

- Install the last version of node
- Install Docker Engine
- Install gh : “sudo apt install gh”
- Connect to GitHub account
- Clone the repo : “gh repo clone jordandefay/school-test”
- Add .env and modif docker-compose
- Generate Prisma’s client with this command : “npx prisma generate”
- You’d then do :
    - docker compose build
    - docker compose up -d db
    - docker compose run —rm migrate
    - docker compose up -d app
- Then the VPS is ready to use
  
Open [http://IP SERVER:3000] with your browser to see the result.

## Learn More

Take a look at the following resources:

- https://chamalhat.com/jordan-defay/index.html
- https://www.linkedin.com/in/jordan-defay-python-dev/
