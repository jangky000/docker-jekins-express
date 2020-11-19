# docker-jekins-express
jenkins를 활용한 자동배포 연습

### Installation

```
cd /
git clone https://github.com/jangky000/docker-jekins-express
cd docker-jekins-express
```

### Run

```
# Docker repo에 로그인 (이미지가 private일 때)
sudo docker login
# 이미지 다운로드
sudo docker pull jangky000/docker-jekins-express
docker run -d -p 3000:3000 jangky000/docker-jekins-express
```
