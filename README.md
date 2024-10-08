## aws-ec2-deploy
#Steps-
1. create an aws ec2 instance
2. open instance id in new tab
3. curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
4. source ~/.bashrc
5. nvm install node
6. git clone your-repo
7. cd your-repo
8. npm i
9. npm run build
10. npm start
11. now go to security tab of instance and add a new tcp rule for port 3000
12. boom your website is being server at ipv4 of yourinstance:3000
