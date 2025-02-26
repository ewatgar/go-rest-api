# Go REST API
### Dependencies
- [gorm](https://github.com/go-gorm/gorm)
- [gorilla/mux](https://github.com/gorilla/mux)
- [air](https://github.com/air-verse/air)
### DB Postgres Config
```
docker run --name db-postgres -e POSTGRES_USER=user -e POSTGRES_PASSWORD=pass -p 5432:5432 -d postgres
```
### Conventional Commits List

| Commit Type | Emoji | Title                    | Description                                                                                                 |
| ----------- | :---: | ------------------------ | ----------------------------------------------------------------------------------------------------------- |
| `feat`      | ✨   | Features                 | A new feature                                                                                               |
| `fix`       | 🐛   | Bug Fixes                | A bug Fix                                                                                                   |
| `docs`      | 📚   | Documentation            | Documentation only changes (README.md)                                                                      |
| `style`     | 🎨   | Styles                   | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)      |
| `refactor`  | 📦   | Code Refactoring         | A code change that neither fixes a bug nor adds a feature                                                   |
| `perf`      | 🚀   | Performance Improvements | A code change that improves performance                                                                     |
| `test`      | 🚨   | Tests                    | Adding missing tests or correcting existing tests                                                           |
| `build`     | 🛠    | Builds                   | Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)         |
| `ci`        | ⚙️   | Continuous Integrations  | Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs) |
| `chore`     | ♻️   | Chores                   | Other changes that don't modify src or test files                                                           |
| `revert`    | 🗑    | Reverts                  | Reverts a previous commit                                                                                   |
