# Dark Theme for Cronicle

![image](https://github.com/user-attachments/assets/79bbb83e-c52b-417f-b35a-42a769304197)



Manually replace `/opt/cronicle/htdocs/css/style.css` with the my `style.css`

Or if you are on Linux, either run

```
sudo wget -O /opt/cronicle/htdocs/css/style.css https://raw.githubusercontent.com/iamumairayub/cronicle_dark_theme/refs/heads/main/style.css
```

or

```
sudo curl -L -o /opt/cronicle/htdocs/css/style.css https://raw.githubusercontent.com/iamumairayub/cronicle_dark_theme/refs/heads/main/style.css
```

Then do 

```
cd /opt/cronicle

systemctl stop cronicle

node bin/build.js dist

systemctl start cronicle
```
