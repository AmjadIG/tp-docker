FROM openjdk
COPY . .
EXPOSE 8080
ENV POSTGRES_URL=127.0.0.1:5432/tp_devops
ENV POSTGRES_USERNAME=tp_devops
ENV POSTGRES_PASSWORD=tp_devops
CMD java -Ddatabase.url=$POSTGRES_URL -Ddatabase.username=$POSTGRES_USERNAME -Ddatabase.password=$POSTGRES_PASSWORD -jar tp-docker-1.0.0.jar
