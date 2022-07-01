<div align="center">
    <h1>Eelectron Application Template</h1>
</div>

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/)
- Mac or Linux (include the wsl linux in window)

## How to use the template

use the tmeplate repository, you need to the command:

```bash
git clone --depth 1 --branch main https://github.com/electron-react-boilerplate/electron-react-boilerplate.git your-project-name

cd your-project-name
```

next, you need to modify the Makefile, set the value of BUILD_REMOTE_REPOSITORIES for your html repository, like:

```bash
BUILD_REMOTE_REPOSITORIES := "https://github.com/your-username/your-html-repository.git"
```

then, you can run the project happily.

## How to build or run the electron

Fisrt, you need to run the npm script command, like:

```bash
npm install
```

After this command is run, it will automatically trigger the command exection of `npm run preinstall`.

The command that  `npm run preinstall` used the makefile command that `make init` to build the html content.

Then, after it is installed, we only use the command that `npm run start` to see the application, like:

```bash
npm run start
```

## How to package the application

package the application, you only use the command:

```bash
npm run package
```
