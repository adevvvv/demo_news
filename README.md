### Установка

```
git clone https://github.com/adevvvv/demo_news.git
```
Зарегистрируй учетную запись [News API](https://newsapi.org/) и получи бесплатный ключ API.

Вставь свой ключ в файл .env
```
docker build -t demo_news .
```
```
docker run -p 8080:8080 demo_news
```
Открой в браузере: http://localhost:8080
