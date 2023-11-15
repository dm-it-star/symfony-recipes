# symfony-recipes

https://symfony.com/doc/current/setup/flex_private_recipes.html
Grant composer Access to the Private Repository
GitHub
In your GitHub account, click your account icon in the top-right corner, select Settings and Developer Settings. Then select Personal Access Tokens.

Generate a new access token with Full control of private repositories privileges. Copy the access token value, switch to the terminal of your local computer, and execute the following command:
    composer config --global --auth github-oauth.github.com [token]