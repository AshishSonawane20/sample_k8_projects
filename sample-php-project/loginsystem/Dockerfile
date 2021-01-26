FROM tomcat:8.0-alpine
LABEL maintainer="ashish.sonawane20@gmail.com"
RUN ["mkdir", "/usr/local/tomcat/webapps/sampleapp"]
RUN ["chmod", "+x", "/usr/local/tomcat/webapps/sampleapp"]
ADD . /usr/local/tomcat/webapps/sampleapp
EXPOSE 8080
RUN ["chmod", "+x", "/usr/local/tomcat/bin/catalina.sh"]
CMD ["/usr/local/tomcat/bin/catalina.sh", "run"]
