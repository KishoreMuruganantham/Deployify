
# Deployify 🌍⚡

Deployify is a **React hosting service** designed to streamline the deployment process. With Deployify, you can deploy your React applications directly from GitHub repositories with just a few clicks. 🎉

### Features 🌟

- **Easy Deployment**: Simply paste the URL of your React GitHub repository and let Deployify handle everything! 🔗
- **Automated Staging**: Utilizes **Redis queue** for efficient staging uploads and deployments, ensuring top-notch performance. 🏎️
- **Seamless Integration**: Works perfectly with React projects, offering a smooth and hassle-free deployment experience. 🛠️
- **Scalable Architecture**: Built with **TypeScript**, ensuring a reliable backend infrastructure capable of handling projects of all sizes. 🏗️
- **Cloud Storage Integration**: Leverages **Backblaze B2** cloud storage for seamless file storage and retrieval. ☁️
- **Dynamic Website URLs**: Your website URLs are dynamically generated upon deployment. 🌐

### Getting Started 🚀

Follow these easy steps to get started with **Deployify**:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YourUsername/deployify.git
   ```

2. **Install dependencies**:
   Install the required packages:
   ```bash
   npm i
   ```

3. **Configure environment variables**:
   Set up your **Backblaze B2** credentials by adding these variables to your environment:
   - `APPLICATION_KEY_ID`
   - `APPLICATION_KEY`
   - `BUCKET_ID`
   - `BUCKET_NAME`

4. **Run the project**:
   - Start the frontend:
     ```bash
     npm run dev
     ```
   - Build the server:
     ```bash
     tsc -b
     ```
   - Start the backend server:
     ```bash
     node dist/index.js
     ```

### Contributors 🌍

- **Kishore Muruganantham** ([@KishoreMuruganantham](https://github.com/KishoreMuruganantham))  
- **Ananda** ([@Bottleneck44](https://github.com/Bottleneck44))  
- **Mukundh A P** ([@MukundhArul](https://github.com/MukundhArul))
- **Mugundhan Y** ([@MugundhanY](https://github.com/MugundhanY))

### License 📝

This project is licensed under the [MIT License](LICENSE). Feel free to fork, modify, and contribute! 🔓

