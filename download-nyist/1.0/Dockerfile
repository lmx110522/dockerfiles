FROM java:8
VOLUME /tmp
ADD download-nyist-0.0.1-SNAPSHOT.jar download-nyist.jar
RUN bash -c 'touch /download-nyist.jar'
ENTRYPOINT ["java","-jar","/download-nyist.jar"]
