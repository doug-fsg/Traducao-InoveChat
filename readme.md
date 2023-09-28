# Tutorial

- cd /home/chatwoot/chatwoot/app/javascript/dashboard/routes/dashboard/settings/automation/
- curl -o constants.js https://raw.githubusercontent.com/doug-fsg/Tradu--o-InoveChat/master/Automa%C3%A7%C3%B5es/automa%C3%A7%C3%B5es.js


- sudo -i -u chatwoot
- cd chatwoot
- rake assets:precompile RAILS_ENV=production
- exit
- systemctl daemon-reload && systemctl restart chatwoot.target