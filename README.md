# dockerPart1-exercise7

I used the same Dockerfiles as in exercises 1.5 and 1.6. The commands that I used to run the containers "docker run -d 
-e 'FRONT_URL=http://localhost:5000' -v '$(pwd)/logs.txt://logs.txt' -p 8000:8000 backend" and "docker run -d
-e 'API_URL=http://localhost:8000/' -p 5000:5000 frontend".
