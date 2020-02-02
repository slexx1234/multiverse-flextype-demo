# Adaptation Multiverse theme by HTML5 to flextype

Это адаптация темы Multiserve от [HTML5UP](https://html5up.net/), под CMS 
[Flextype](https://flextype.org/en). 

Почему я не залил темы отдельным репозиторием? Да потому что тема требует наличие не 
стандартных Entries и Fieldsets. Хотя мне можно было написать инструкцию длинной в 
киллометр объясняющую как нужно устанавливать тему, нормальные движки так не работают
поэтому здесь весь двидок со всем необходимым для запуска.

А да, установка:

```bach
git@github.com:slexx1234/multiverse.git
cd multiverse/site/plugins/admin
composer install
npm install
gulp

cd ../../../

cd site/plugins/site
composer install

cd ../../../

cd site/themes/default
npm install
gulp
```
