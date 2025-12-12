# Reeve CI / CD - Pipeline Step: NPM CLI

This is a [Reeve](https://github.com/reeveci/reeve) step for executing NPM and Node.js commands.

## Configuration

See the environment variables mentioned in [Dockerfile](Dockerfile).

Use `command` to specify the command to be executed, e.g.:

```yaml
command: ["npm", "run", "build"]
```
