# Amazon Web Services (aws) Tutorial
aws solution-architect-tutorial by sunil dhiman

# How to install Web-Server in Linux Based Instances
```Note:- If you are Root User then you don't need to write `sudo` before command line.``` 
```ruby
sudo yum install httpd -y
```

```ruby
sudo service httpd start
```
```ruby
sudo service httpd status
```

>Now here your server is started. If you want to live your own application, PHP file, HTML file then you can go for it. For example: as a HTML File, then 

```ruby
sudo vim  /var/www/html/index.html
```
```ruby
sudo chkconfig httpd on 
```
>Now your file will be uploaded, you can search through your Server Public IP Address


