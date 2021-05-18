# Docker-and-Kubernetes
Here, I am Exploring more about docker and kubernetes. Will provide day-to-day logs of what I learned.


## Docker installation for windows:

1. install docker engine
2. vim editor on powershell
3. creating docker file

Command => <br>
**vim Dockerfile** 
```
FROM alpine
RUN apk add --update redis
CMD ["redis-server"]`
```
**docker build -t bydockerfile .**

![image](https://user-images.githubusercontent.com/46487696/118637987-fe850b00-b7f3-11eb-9b07-f2de99bbde11.png)

![image](https://user-images.githubusercontent.com/46487696/118638239-3db35c00-b7f4-11eb-9a73-8205a7d45738.png)
![image](https://user-images.githubusercontent.com/46487696/118638161-2b392280-b7f4-11eb-9466-704c875b2346.png)

**Docker Desktop logs:**

![image](https://user-images.githubusercontent.com/46487696/118638481-8539e800-b7f4-11eb-8fab-4dcf09c2ee8f.png)

## Dockerfile:

![image](https://user-images.githubusercontent.com/46487696/118641400-bcf65f00-b7f7-11eb-86c8-61aaf410f45c.png)
![image](https://user-images.githubusercontent.com/46487696/118641414-bff14f80-b7f7-11eb-92fe-816ad3a263aa.png)


## docker image background process by Dockerfile:

![image](https://user-images.githubusercontent.com/46487696/118641029-48232500-b7f7-11eb-9db9-68b9be61b6e3.png)
![image](https://user-images.githubusercontent.com/46487696/118641520-dd261e00-b7f7-11eb-974a-884fe4219dbe.png)
  
![image](https://user-images.githubusercontent.com/46487696/118644403-62f79880-b7fb-11eb-8c10-bee5c2947e7e.png)



