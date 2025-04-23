# Using K6 for load testing performance

### Dependencies
- Docker
- Node to run scripts
- npm or pnpm package manager
- notepad or some IDE (like VSC, Cursor, etc.)

### Usage

This will download the Docker image for later usage.
```
pnpm docker:setup
```

Open script.js and modify the URL to call, you can also customize some parameters in the options object.

```
{
  vus: amount of virtual users (number)
  duration: duration of the test, ex. '30s' (string)
}
```

This will run the test
```
pnpm docker:run
```
