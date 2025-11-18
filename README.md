# Test your GPU performance using QuokIT

- Get Early Access first: [QuokIT](https://www.quok.it)

---

- Rent a GPU from any provider
- Run this commands in terminal

## Install Quok
```
sudo install -d -m 0755 /etc/apt/keyrings && curl -fsSL https://repo.quok.it/quok.asc | gpg --dearmor | sudo tee /etc/apt/keyrings/quok.gpg >/dev/null && echo 'deb [signed-by=/etc/apt/keyrings/quok.gpg] https://repo.quok.it/ cross main' | sudo tee /etc/apt/sources.list.d/quok-stable.list >/dev/null && sudo chmod 0644 /etc/apt/keyrings/quok.gpg /etc/apt/sources.list.d/quok-stable.list && sudo apt-get update
```
```
sudo apt install quok
```

## Initialize Quok
```
quok init
```
- Enter the API key (check email once you have access)
- If you need access message the quok support team in gensyn discord

## Run Quok 
```
quok auditme
```
- Enter the GPU provider
- Wait for checks to complete
- Check your quok dashboard

<img width="1901" height="787" alt="image" src="https://github.com/user-attachments/assets/99450f0a-ffe3-4700-87c0-7496380d8e05" />
