# Laravel-vue-3-starter

It's a pre-configured project using Laravel 8 and Vue 3

to get it up and run just clone it and enhoy coding :

     git clone https://github.com/boussadjra/laravel-vue-3-starter.git

     cd laravel-vue-3-starter



then install backend modules by running 

     composer install

and front-end modules :

     npm install
     
創建.env文件並運行：

    php artisan key:generate
在拉動git項目後，這對我有用。

創建.env文件並生成密鑰後，運行以下代碼：

    php artisan cache:clear 
    php artisan config:clear
    
設定好後 建本地server
    
    執行php aritsan serve 

