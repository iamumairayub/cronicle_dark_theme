# Dark Theme for Cronicle

![image](https://github.com/user-attachments/assets/a7492005-7a6d-4dbb-ac1c-4852a190f4e3)

![image](https://github.com/user-attachments/assets/ae509dcd-1686-4e59-8a2d-67b8d7a568df)


# Setup

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
