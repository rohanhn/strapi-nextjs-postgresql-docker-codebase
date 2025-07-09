# Dùng image Node.js 22 chính thức từ Docker Hub
FROM node:22

# Thư mục làm việc trong container
WORKDIR /app

# Copy toàn bộ mã nguồn từ host vào container
COPY . .

# Cài đặt dependencies bằng Yarn (hoặc NPM nếu bạn dùng NPM)
RUN yarn install

# Mở cổng mặc định của Strapi (trong container)
EXPOSE 1337

# Lệnh khởi động ứng dụng Strapi ở chế độ phát triển
CMD ["yarn", "develop"]
