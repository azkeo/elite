# elite
# ==================== #
#  Operating Systems   #
# ==================== #
.DS_Store
Thumbs.db
desktop.ini

# ==================== #
#    Frontend (Web)    #
# ==================== #
# Build files
/dist/
/build/
/.next/
/.nuxt/

# Compiled/Cached files
*.min.css
*.min.js
*.map
*.sass-cache

# ==================== #
#      Backend         #
# ==================== #
# Node.js
node_modules/
npm-debug.log*
yarn-error.log
.pnp/
.pnp.js

# PHP
/vendor/
.phpunit.result.cache
.env.php

# ==================== #
#    Configuration     #
# ==================== #
# Environment files
.env*
!.env.example

# Sensitive configs
/config.json
/secrets/
/payment-keys/

# ==================== #
#      Databases       #
# ==================== #
# SQL
*.db
*.sql
/db_backups/

# NoSQL
/mongo_data/
/redis_cache/

# ==================== #
#    Development       #
# ==================== #
# IDEs
.vscode/
.idea/
*.swp

# Testing
/coverage/
/.nyc_output/
/__tests__/__snapshots__/

# ==================== #
#  eCommerce Specific #
# ==================== #
# Media uploads
/uploads/
!/uploads/sample/

# Temporary files
/temp/
*.log
*.tmp

# Payment processors
/stripe/
/paypal/
/ssl_certs/
# Docker (if used)
docker-compose.override.yml
/.dockerignore

# Lerna (monorepos)
/lerna-debug.log
touch .gitignore
git status --ignored
