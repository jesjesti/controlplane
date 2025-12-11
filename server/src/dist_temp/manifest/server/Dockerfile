FROM openjdk:21
COPY ./app/start_app.sh /start_app.sh
COPY ./app/server_manifest.jar /server_manifest.jar
RUN chmod -R 755  /start_app.sh
ENTRYPOINT /start_app.sh