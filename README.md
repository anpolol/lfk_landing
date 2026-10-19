# скопировать на сервер
rsync -av --delete --exclude='.git' --exclude='.DS_Store' /Users/polinaandreeva/Projects/lfk_landing/ ru_vdsina:/var/www/lfk_landing/