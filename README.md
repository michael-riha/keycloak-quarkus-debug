
# Keycloak Quarkus Remote DEbug via `vsc`

This is just the first attempt to add a `vsc` debugger for remote debugging.

TODO:
- How to set interactive breakpoints?
- Add one Extension example to interactive debug
- iteratively improve, as usual 🤞

---

# keycloak-quarkus-debug
 
* import pom.xml as Maven project
* find `KeycloakMain` class and set a breakpoint
* run `docker-compose up` - imports [realm-config/local](./realm-config/local) and starts KC in debug mode. 
* in IDEA create `Remote JVD debug` on `5005` port and start debugging
