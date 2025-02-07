<div align="center">
  <a href="http://netflix-clone-with-tmdb-using-react-mui.vercel.app/">
    <img src="./public/assets/netflix-logo.png" alt="Netflix Clone Logo" width="100" height="32">
  </a>
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/9c3aeb8e-8fc1-478b-bd59-907388c20e11" alt="Netflix Clone Preview">
</div>

---

## 📖 Blog Post
📌 CICD Projelendirmesi için blog yazımı okuyabilirsiniz:  
👉 **[DevSecOps: Deploying a Netflix Clone CI/CD Project on AWS EKS](https://www.serdarbayram.net/devsecops-deploying-a-netflix-clone-ci-cd-project-on-aws-eks.html)**

---

## 🚀 Install with Docker

```bash
docker build --build-arg TMDB_V3_API_KEY=your_api_key_here -t netflix-clone .
docker run --name netflix-clone-website --rm -d -p 80:80 netflix-clone
