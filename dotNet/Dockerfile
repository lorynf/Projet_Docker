FROM ubuntu:latest
RUN apt-get update && apt-get install -y mono-complete wget
RUN wget http://erebe-vm5.i3s.unice.fr/artifactory/libs-release-local/dotnet/server.exe

CMD ["mono","server.exe"]
EXPOSE 9090