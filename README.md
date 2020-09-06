| Backend           |                |        | Responsibility                                        |
|-------------------|----------------|--------|-------------------------------------------------------|
| dist              |                |        | all the JS files are here                             |
| lib               |                |        | all the TS files are here                             |
|                   | config         |        | app config files                                      |
|                   |                | app.ts | app starting point                                    |
|                   | controllers    |        | request managers                                      |
|                   | modules        |        | schemas, interfaces, services                         |
|                   | routes         |        | endpoints                                             |
|                   | environment.ts |        | stores environment variables                          |
|                   | server.ts      |        | HTTP server that listens to server port               |
| .gitignore        |                |        |                                                       |
| package-lock.json |                |        |                                                       |
| package.json      |                |        | npm package list                                      |
| tsconfig.json     |                |        | specify the root level files and the compiler options |
