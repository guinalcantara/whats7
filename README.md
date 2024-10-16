# whats7

docker run --name whaticketdb -e POSTGRES_PASSWORD=whaticketdb -e POSTGRES_USER=whaticket -e POSTGRES_DB=whaticket --restart always -p 5432:5432 -d postgres:latest

"start": "react-scripts start",
"build": "react-scripts build",

ENV do BACKEND

NODE_ENV=
BACKEND_URL=http://localhost
FRONTEND_URL=http://localhost:3000
PROXY_PORT=443
PORT=8080

DB_DIALECT=postgres
DB_HOST=localhost
DB_PORT=5432
DB_USER=postgres
DB_PASS=@As13071987
DB_NAME=aula01

JWT_SECRET=kZaOTd+YZpjRUyyuQUpigJaEMk4vcW4YOymKPZX0Ts8=
JWT_REFRESH_SECRET=dBSXqFg9TaNUEDXVp6fhMTRLBysP+j2DSqf7+raxD3A=

REDIS_URI=redis://:@127.0.0.1:6379
REDIS_OPT_LIMITER_MAX=1
REDIS_OPT_LIMITER_DURATION=3000

==========================================================
COMANDOS DO BACKEND

npm install
npm run build
npx sequelize db:migrate
npx sequelize db:seed:all
npm start

==========================================================
ENV do FRONTEND

REACT_APP_BACKEND_URL=http://localhost:8080
REACT_APP_HOURS_CLOSE_TICKETS_AUTO = 24
REACT_APP_FACEBOOK_APP_ID=

==========================================================
COMANDOS DO FRONTEND

npm install
npm start