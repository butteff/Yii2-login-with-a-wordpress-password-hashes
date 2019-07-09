# Yii2 login with a wordpress password hashes

To import a wordpress users to Yii2 just do this:
1. import all the data, that you need, to the User table in your database.
2. You can have there Yii2 or/and WordPress hashes for passwords
3. Replace vendor/yiisoft/yii2/base/Security.php with the file from this repo.

What the file does:
instead of exception of invalid hash it starts to use a wordpress functions for another one password validation.
It all is still secure. Enjoy.
