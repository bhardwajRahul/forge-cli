# Release Instructions

1. Pull down the latest changes on the current stable branch
2. Update the version in [`config/app.php`](./config/app.php)
3. Compile the binary with

```zsh
./forge app:build
```

4. Commit all changes
5. Push all commits to GitHub
6. [Create a new GitHub release](https://github.com/laravel/forge-cli/releases/new) with the release notes
