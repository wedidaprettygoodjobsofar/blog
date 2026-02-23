[![Netlify Status](https://api.netlify.com/api/v1/badges/f158275c-4bbb-4eeb-b63d-0ed1122f6107/deploy-status)](https://app.netlify.com/projects/iloveggbond/deploys)

# Local Deployment

确认你安装了 node 和 git

```bash
npm install -g n
sudo n latest
npm install -g npm@latest
rm -rf node_modules package-lock.json
npm cache clean --force
npm install
npm run netlify
```
