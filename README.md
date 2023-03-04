# Thamindu-Sulakshana


<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=1B40DE&width=600&lines=HELLO%2C+My+name+is+Thamindu+Sulakshana;Be+Welcome!+%3A)" alt="Typing SVG" /></a>


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=ThaminduSulakshana&theme=yeblu&show_icons=true)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)



{
  "name": "snk",
  "description": "Generates a snake game from a github user contributions grid",
  "version": "2.2.1",
  "private": true,
  "repository": "github:platane/snk",
  "devDependencies": {
    "@sucrase/jest-plugin": "3.0.0",
    "@types/jest": "29.4.0",
    "@types/node": "16.11.7",
    "jest": "29.4.3",
    "prettier": "2.8.4",
    "sucrase": "3.29.0",
    "typescript": "4.9.5"
  },
  "workspaces": [
    "packages/**"
  ],
  "jest": {
    "testEnvironment": "node",
    "testMatch": [
      "**/__tests__/**/?(*.)+(spec|test).ts"
    ],
    "transform": {
      "\\.(ts|tsx)$": "@sucrase/jest-plugin"
    }
  },
  "scripts": {
    "type": "tsc --noEmit",
    "lint": "yarn prettier -c '**/*.{ts,js,json,md,yml,yaml}' '!packages/*/dist/**' '!svg-only/dist/**'",
    "test": "jest --verbose --passWithNoTests --no-cache",
    "dev:demo": "( cd packages/demo ; yarn dev )",
    "build:demo": "( cd packages/demo ; yarn build )",
    "build:action": "( cd packages/action ; yarn build )"
  }
}
