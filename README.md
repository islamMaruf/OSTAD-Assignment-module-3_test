

## Prerequisites

- Node Version 22


### 1. For Run This Applications
```bash
# install packages
npm install 

# Testing The Applications
npm run check

# For Run the application
npm start
```


### Deployment Process
1. **Cleanup**: Removes existing process if running
   ```bash
   pm2 delete node-app || true
   ```

2. **Start Application**: Launches with absolute path
   ```bash
   pm2 start "./src/server.js" --name node-app
   ```

3. **Save Process List**: Persists PM2 configuration
   ```bash
   pm2 save
   ```

### About The Applications
1. **Route**: This Application has 2 route
   ```bash
   / # this will show a hello world page
   ```
      ```bash
   /api # this will response a json
   ```

2. **Default Port**: By Default this application will run on port 3000

### Images

![Screenshot from 2025-03-13 22-06-39](https://github.com/user-attachments/assets/7de651c7-7167-4161-8c45-c207916dd271)
![Screenshot from 2025-03-13 22-05-10](https://github.com/user-attachments/assets/cab79cf9-d871-4315-8e40-ff57ebd8a5e4)

![Screenshot from 2025-03-13 22-04-51](https://github.com/user-attachments/assets/4295cf3d-583d-4090-ac54-dcad4b5bbdee)


