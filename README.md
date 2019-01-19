# Yii2 login with a wordpress password hashes

To import a wordpress users to Yii2 just do this:
1. import all the data, that you need, to User table in your database.
2. You can have there Yii2 or WordPress hashes for passwords
3. Replace vendor/yiisoft/yii2/base/Security.php with the file from this repo.

What the file does:
instead of exceprion of invalid hash it starts to use a wordpress functions for another one password validation.
So my changes are: exception remove and just copy\paste of some wordpress functions with a little adaptation.
It all is still secure. Enjoy.