# DRF\_hide\_admin\_token

When using Django Rest Framework's authentication tokens, you need to add `rest_framework.authtoken` to your INSTALLED_APPS. This will display the Tokens table in the admin panel whether you want it there or not. If you fall into the 'not' category, this is the app for you.

## Installation

1. Add `git+https://github.com/HappyTepid/Hide-DRF-Admin-Token.git` to your requirements.txt
2. Add `"DRF_hide_admin_token"` to your INSTALLED_APPS **after** `"rest_framework.authtoken"`