docker build -t fetch-data ./ 
docker run -it -v "$(pwd):/app" -p 3000:3000 fetch-data:latest bash 
npm start
