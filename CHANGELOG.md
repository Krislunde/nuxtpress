# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.2] - 2020-02-15

### 🌟 Highlights
- Now using Nuxt 2.11
- Docker compose is now v3, and the mysql container now uses MariaDB v10.4.12.

### 🐛 Bug Fixes 
- Fix undefined key on homepage when getting an error in post retrieval.

### 🦄️ Improvements
- Improved the docker-compose file for easier use, such as naming the volumes.
- Improve the lint-staged files by adding relevant tests and stylelint automatically
- Made the TemporaryPostData helper component only display in development mode

### 🏡 Chore
- Add some missing files to .gitignore, including WP's debug.log   

### ⚓ Dependency Upgrades 
- Upgrade Nuxt from 2.10 to 2.11

## [0.0.1] - 2019-12-03
### 🌟 Highlights

- Initial release of NuxtPress
  - Docker compose for quickly starting development
  - Page components that help you automatically map WordPress API calls to your pages
  - Recommend plugins included from installation
  - Recommended development tools pre-setup, lik Jest, ESLint, Prettier, Stylelint, lint-staged, storybook and more 

For reference:

🌟 Highlights  
🐛 Bug Fixes  
🚀 Features  
🦄️ Improvements
💅 Refactors  
🔥 Performance  
📝 Examples  
🏡 Chore  
👓 Tests  
⚓ Dependency Upgrades  
💖 Thanks to  
