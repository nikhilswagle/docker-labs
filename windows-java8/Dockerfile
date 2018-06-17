# escape=`

# Base Image
FROM microsoft/windowsservercore

# Metadata indicating an image maintainer.
LABEL maintainer="nikhil.swagle@gmail.com"

COPY jre1.8.0_111 C:\Java\jre\

ENV JAVA_HOME C:\Java\jre

RUN echo %JAVA_HOME%

RUN setx PATH "%PATH%;%JAVA_HOME%\bin"

RUN echo %PATH%

RUN java -version