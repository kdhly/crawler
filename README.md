# quick start

get and run golangbbs &emsp;&emsp;&emsp;&emsp;[(中文)](/READMECN.md)

## 1. Source mode
	
	git clone https://github.com/kdhly/crawler.git  
	cd crawler  
	go run main.go

### components:

	go get github.com/Sirupsen/logrus  
	go get github.com/gin-contrib/sessions  
	go get github.com/gin-gonic/gin  
	go get github.com/go-sql-driver/mysql  
	go get github.com/mattn/go-sqlite3  
	go get github.com/quasoft/memstore  
	etc  



# configuration file: bbs_config_main_i18n_xxx.json
you can change the IPAddr to 127.0.0.1 to visit it only on your local machine, The default database is sqlite3 , you can import .sql in golangbbs/dist/mysql directory to your mysql database and change DbType to "mysql" if you want to use mysql.

# Structure and Features:
golang  
database: mysql
1. Adjustable number of grabbing threads and file saving threads;  
2. Automatically save progress in configuration file and MySQL when exiting;  
3. Portable design;   

#### Notice:
1. Before using, please adjust the configuration file, grab the website URL and regular filter, and import MySQL library; 


## Contact
mail: golangbbs@gmail.com  
or visit link: http://www.golangbbs.com/?page=bbs&category=XWdNEvaL_go

## tips:
If you have good projects or suggestions, we can help you realize it
## Special thanks:
@fhst, @kdhly, and all function modules used in the project structure and plug-ins; and other function module not listed;

## Give me a star
If you like or plan to use this project,please give me a star, thank you!

## Donation
If this project makes you feel good, You can donate to the following link to better support the development of this project and the team:
##### https://paypal.me/golangbbs

## Screenshots ：<br /><br />
#### mainpage 
>![11](/static/img/screenshots/mainpage.jpg)  <br /><br />
