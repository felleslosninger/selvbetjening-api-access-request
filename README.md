# Maskinporten Onboarding: Backend

## Development

Run application with [Spring Profile](https://www.baeldung.com/spring-profiles) `dev` to use the default development environment.

Additionally, you must inject the _ansattporten client secret_ in the context.

An easy way to manage this is with the [EnvFile](https://plugins.jetbrains.com/plugin/7861-envfile) plugin and the following [.env](.env) file:
```
# client secret associated with `forenklet_onboarding_dev`
ANSATTPORTEN_CLIENT_SECRET=<thesecret>
```
