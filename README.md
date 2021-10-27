#### How to use

1. `git clone`

```sh
git clone https://github.com/tincochan/pandoc-nextjs-server.git
cd pandoc-nextjs-server
```

2. Build a docker image

```sh
docker build -t pandoc-nextjs-server .
docker run -p 3000:3000 -it --rm --name pns pandoc-nextjs-server
```

3. Go to http://localhost:3000
4. Have fun!

---

(c) Tinco Chan 2021
