# springboot-rabbitmq-example
How to use RabbitMQ with Publisher and Consumer Example

Install RabbitMQ in windows :
-----------------------------
1. Download and install ERlang http://erlang.org/download/otp_win64_22.3.exe
2. Downlaod and install RabbitMQ https://github.com/rabbitmq/rabbitmq-server/releases/download/v3.8.8/rabbitmq-server-3.8.8.exe
3. Go to RabbitMQ Server install Directory C:\Program Files\RabbitMQ Server\rabbitmq_server-3.8.3\sbin
4. Run command rabbitmq-plugins enable rabbitmq_management
5. Open browser and enter http://localhost:15672/ to redirect to RabbitMQ Dashboard
6. Also we can Open it with IP Address http://127.0.0.1:15672
7. Login page default username and password is guest 
8. After successfully login you should see RabbitMQ Home page

Install RabbitMQ in Linux : https://www.youtube.com/watch?v=eazz-Je4HAA

su - root
password
bash

sudo apt-get update
 sudo apt-get install erlang
sudo apt-get install rabbitmq-server
 sudo systemctl enable rabbitmq-server
sudo systemctl start  rabbitmq-server
sudo systemctl status  rabbitmq-server
sudo rabbitmq-plugins enable rabbitmq_management

http://0.0.0.0:9292/order/saja

{
       "name":"email@g.com",
    "qty":3,
      "price":41
}

best explanation :: https://www.cloudamqp.com/blog/part1-rabbitmq-for-beginners-what-is-rabbitmq.html