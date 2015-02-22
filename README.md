Minimal web app combining CDI (Weld) and Jetty

After spending more time than I care to admit hunting for the right
combination of Maven, web.xml and Jetty settings, I thought it might
make sense to put this online somewhere.

Build and start it with `mvn jetty:run`, then connect to the running
server at http://localhost:8080. If you see the message "Hello from
CDI", everything is fine.
