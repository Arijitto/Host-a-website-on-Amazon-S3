### **Host a Website on Amazon S3**  

Amazon S3 (Simple Storage Service) allows you to **host static websites** (HTML, CSS, JavaScript) without needing a web server. It provides **high availability, scalability, and cost-effectiveness**.  

### **Steps to Host a Website on S3:**  
1. **Create an S3 Bucket** – Name it the same as your domain (e.g., `example.com`).  
2. **Enable Static Website Hosting** – Configure the bucket for web hosting.  
3. **Upload Website Files** – Add HTML, CSS, and JavaScript files.  
4. **Set Permissions** – Make files publicly accessible using a **Bucket Policy**.  
5. **Optional: Configure a Custom Domain** – Use **Amazon Route 53** or another DNS provider.  
6. **Enable Security & Optimization** – Use **CloudFront** for caching and HTTPS support.  

S3 offers a simple and scalable way to host static websites with minimal setup.
