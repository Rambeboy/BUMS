## BUMS BOT

![Bums](https://github.com/user-attachments/assets/d3515d2c-8c79-4030-9670-dc694d9855fe)

---

## BOT FEATURE

✔️ Auto tap
✔️ Auto daily
✔️ Auto task
✔️ Auto upgrade

---

## REQUIREMENTS

- Nodejs
- Git


---

## INSTALL MODULES

1. Clone Project Repository
   ```bash
   git clone https://github.com/Rambeboy/BUMS.git && cd BUMS
   ```

2. Install Depedencies
   ```bash
   npm install
   ```
3. Create two files: `data.txt` and `proxy.txt`

For those using multiple accounts, it's recommended to use a proxy (if using only one account, there's no need to create the proxy.txt file).

---

## PROXY FORMAT:

```bash
http://username:passwoord@hostname:port
socks5://username:password@hostname:port
```

---

# GET DATA

In the `data.txt` file, you need to have the following format:

query_id=xxx or user=xxxx

![Capture](https://github.com/user-attachments/assets/6db0b3ed-86fe-4cf7-b9c3-9dde4c0f2efb)

---

# CONFIGURATION

This configuration option of `config.json`

```js
{
    "maxUpgradeCost": 1000000
}
```

---

# RUN TOOL
1. **No Proxy**
   ```bash
   node main.js
   ```
2. **Proxy**
   ```bash
   node bums-proxy.js
   ```

---
   
