# Nginx Commands Windows

[Official Docs](http://nginx.org/en/docs/beginners_guide.html)

**Note**:
In order to execute these commands, you need open CMD in Nginx directory on your windows machine


## Start Nginx
```start nginx```


## Reload After Making Changes
```nginx -s reload```


## Nginx Confgiration Check
```nginx -t```

## Quit Nginx (close connection)
```nginx -s quit```


## Terminate Nginx Process/es (Task manager)
```@taskkill /f /im nginx.exe```


## Clear Cache
* Set expiry headers inside location blocks or
* Replace current folders structure with the old one
