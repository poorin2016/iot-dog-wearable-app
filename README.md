# iot-dog-wearable-app
IoT Dog Wearable Web Application - IP 68130669
ขั้นตอนการ Push Code ขึ้น GitHub
# Clone repository ที่สร้างไว้
git clone https://github.com/<username>/iot-dog-wearable-app.git
cd iot-dog-wearable-app

# Copy ไฟล์ทั้งหมดเข้าไปในโฟลเดอร์ repo
cp -r public/ css/ js/ scripts/ nginx.conf Dockerfile docker-compose.yml README.md .

# Upload ไป GitHub
git add .
git commit -m "Initial commit - IoT Dog Wearable Web Application"
git push -u origin main
