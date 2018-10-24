# gitignore
提供包含常见规则的.gitignore文件的下载，方便项目初始化。

## Usage

Download from uri (use curl for example): 

```
curl -O "https://github.com/czzonet/gitignore/raw/master/gitignore"
```

Then rename to ".gitignore" which just add a dot to the downloaded filename "gitignore".

## Rules

```bash
.DS_Store
node_modules
/dist

# local env files
.env.local
.env.*.local

# Log files
npm-debug.log*
yarn-debug.log*
yarn-error.log*

# Editor directories and files
.idea
.vscode
*.suo
*.ntvs*
*.njsproj
*.sln
*.sw*
```
