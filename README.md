# SPECIAL Dispatcher
This docker container runs a single dispatcher to redirect both to Keycloak and to Kong. This is because we use keycloak to authenticate our users and Kong for routing requests.

# Configuration
This service will always connect to a network called "special_demonstrator". Therefor you must make sure a docker overlay network named "special-demonstrator" exists.