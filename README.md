# Sosmed Main

## Dependencies
- Docker
- Docker Compose

## How to Run
1. Clone this repo
```shell
git clone https://github.com/fauzanardh/sosmed_main.git
```
2. Clone the submodules
```shell
git submodule update --init --recursive
```
3. Build and Run
```shell
docker-compose up --build
# or if you want it to run in a background
docker-compose up --build -d
```
4. Access the App using `http://localhost/`
6. (optional) Access the API Server using `http://localhost/api/` 
7. (optional) How to Update the Submodules (if there's a new commit in the submodules)
```shell
git submodule update --remote --merge
```
