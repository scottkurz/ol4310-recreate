# ol4310-recreate
recreate of https://github.com/OpenLiberty/open-liberty/issues/4310

# Recreate Steps
1. clone, build with `mvn package`
2. create an 18.0.0.2 WLP server with [liberty-config/server.xml](liberty-config/server.xml).
3. Copy over 

          cp target/gs-mysql-data-0.1.0.jar .../newServer/apps
          
## NOTES:         
1. I hit basically the same thing in dropins (as apps)
1. Assuming this problem was fixed, the app would fail lacking access to the mysql server, so just relevant for recreate of 4310.





