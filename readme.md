# Приложение для ведения ферм под airdrop

Приложение имеет 2 версии: облачная ([платная](!https://drop-hunter.pro/)) 
и бесплатная для запуска у себя. В этом репозитории бесплатная версия.

со списком поддерживаемых функций можно ознакомиться на [сайте](!https://drop-hunter.pro/)
 на главной странице по вкладке интеграции

### Как запустить
1) Установить docker-compose
> Windows https://docs.docker.com/desktop/install/windows-install/
> 
> Macos https://docs.docker.com/desktop/install/mac-install/
> 
> Linux https://docs.docker.com/desktop/install/linux-install/
2) склонировать репозиторий к себе
> git сlone https://github.com/hardstylez72/cry-service.git
3) Выполнить из консоли куда скачали репозиторий команду
>  docker-compose up 
4) открыть приложение у себя в браузере
> http://localhost:4321/
5) если что-то не работает 
> docker-compose restart

<br/>

### Для обновления на последнюю версию:
1) Выполнить из консоли куда скачали репозиторий команду
> docker-compose pull
2) Запустить
> docker-compose up 

### Безопасность
все приватники хранятся у вас на машине, приложение делает только
запросы на выбранные вами defi приложения и слушает цены на токены на binance

### Зачем?
люблю заниматься разработкой 





