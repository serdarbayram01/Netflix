<div align="center">
  <a href="http://netflix-clone-with-tmdb-using-react-mui.vercel.app/">
    <img src="./public/assets/netflix-logo.png" alt="Netflix Clone Logo" width="100" height="32">
  </a>
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/9c3aeb8e-8fc1-478b-bd59-907388c20e11" alt="Netflix Clone Preview">
</div>

---

## 🛠️ DevSecOps CI/CD - Netflix Clone Project

Bu proje, AWS EKS üzerinde çalışan bir **Netflix Clone** uygulamasının **DevSecOps yaklaşımıyla** nasıl CI/CD süreçleri kullanılarak dağıtılacağını göstermektedir.  
**Kubernetes,Docker,Docker hub,Jenkins, Sonarqube, Nexus,OWASP, Trivy, Docker-Scout** gibi araçlarla tam otomatik ve güvenli bir yazılım teslim süreci oluşturulmuştur.  

📌 **Projede Kullanılan Teknolojiler:**  
<br>✅ AWS  
<br>✅ EKS  
<br>✅ EC2  
<br>✅ Jenkins  
<br>✅ Nexus  
<br>✅ DevOps Security Tools  
<br>✅ Docker & Kubernetes  

---

## 📌 Proje Topolojisi

Aşağıdaki diyagram, sistemin genel mimarisini göstermektedir:

<div align="center">
  <img src="https://github.com/user-attachments/assets/4452878a-73e9-4ab1-a0c0-a6a9c7daee29" alt="Project Topology">
</div>

---

## 📖 Blog Post
📌 Daha detaylı bilgi için blog yazısını okuyabilirsiniz:  
👉 **[DevSecOps: Deploying a Netflix Clone CI/CD Project on AWS EKS](https://www.serdarbayram.net/devsecops-deploying-a-netflix-clone-ci-cd-project-on-aws-eks.html)**

---

## 🚀 Install with Docker

```bash
docker build --build-arg TMDB_V3_API_KEY=your_api_key_here -t netflix-clone .
docker run --name netflix-clone-website --rm -d -p 80:80 netflix-clone
