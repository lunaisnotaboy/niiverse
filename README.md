# Niiverse
Niiverse. A Miiverse clone based off of Indigo/shell.

## Installation
1. Install the latest version of Go from [golang.org](https://golang.org/dl/) or from the official gopher repository.
2. Download the .ZIP file or clone the repository like any other project.
3. Install all the dependencies with `go get ./...`.
4. Set up a MySQL server and import structure.sql.
5. Modify the config.json file to your liking.
6. Build the server with `go build` and then run the new program that is created, or use `go run *.go` (Linux/MacOS only).
7. Make an account, give yourself admin through the MySQL CLI (`UPDATE users SET level = 9 WHERE id = 1`, for example) or your favorite database management interface (e.g. PHPMyAdmin), and start making some communities!

## Credits
- lunaisnotaboy (a.k.a. stampylongr) for shell & hosting
- PF2M & co. for creating Indigo
- The Nii U Team for their support

## Anything else?
Not much yet, thanks for asking.
