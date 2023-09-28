# Tutorial

<details>
<summary>Manual de tradução automação</summary>

```bash
cd /home/chatwoot/chatwoot/app/javascript/dashboard/routes/dashboard/settings/automation/
```
```bash
curl -o constants.js https://raw.githubusercontent.com/doug-fsg/Tradu--o-InoveChat/master/Automa%C3%A7%C3%B5es/automa%C3%A7%C3%B5es.js
```

```bash
sudo -i -u chatwoot
```
```bash
cd chatwoot
```
```bash
rake assets:precompile RAILS_ENV=production
```
```bash
exit
```
```bash
systemctl daemon-reload && systemctl restart chatwoot.target
```
</details>

<details>
<summary>Manual de tradução macros</summary>

```bash
cd /home/chatwoot/chatwoot/app/javascript/dashboard/routes/dashboard/settings/macros/
```
```bash
curl -o constants.js https://raw.githubusercontent.com/doug-fsg/Traducao-InoveChat/master/Macros/macros.js
```

```bash
sudo -i -u chatwoot
```
```bash
cd chatwoot
```
```bash
rake assets:precompile RAILS_ENV=production
```
```bash
exit
```
```bash
systemctl daemon-reload && systemctl restart chatwoot.target
```
</details>
