# Knox Rate-A-Service


URL: https://yamankoudmani.github.io/revue/

## Installation

```bash
git clone https://github.com/Lanseuo/revue.git
cd revue
```

install dependencies for client
```bash
cd client
npm install
```

install dependencies for server
```bash
cd ../server
pip3 install -r requirements.txt
```

add config file
```bash
nano config.py
```
```python
flask_secret_key = "CHANGEME"
image_upload_folder = ".../revue/server/images"
```

## Usage

```bash
cd client

# serve with hot reload at localhost:8080
npm run serve

# build for production with minification
npm run build
```

```
cd server
flask run
```

## Made with

- [Vue.js](https://vuejs.org/) - JavaScript Framwork
- [axios](https://github.com/axios/axios) - HTTP client
- [Flask](https://flask.pooco.com) - Web Framework
- [MongoEngine](https://github.com/MongoEngine/mongoengine) - Object-Document-Mapper for MongoDB

