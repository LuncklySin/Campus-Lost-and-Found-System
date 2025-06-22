# 校园失物招领系统  - 更多在微信 ： jackSinWu --在咸鱼：不知名选手java小鑫 --B站：不知名选手java小鑫 关注可打9折

#### 介绍  
基于 **Spring Boot** 和 **Vue.js** 构建的校园失物招领系统，旨在帮助学生快速寻找丢失物品或归还捡拾的物品，提升校园生活的便利性和互动性。  

**技术栈**：  
- 前端：Vue.js  
- 后端：Spring Boot，MyBatis  
- 数据库：MySQL  


**图片介绍**：  
![image](https://github.com/user-attachments/assets/c91642c5-aaf8-4b7c-936a-8dd18f4aba49)
![image](https://github.com/user-attachments/assets/c3f23492-8b58-4ed8-bc05-0132987fc8d2)
![image](https://github.com/user-attachments/assets/8640f559-0b10-4bc4-9f6c-acc4af8bd066)
![image](https://github.com/user-attachments/assets/b8d6686f-a720-4db6-9f20-2e2b002e5b72)
![image](https://github.com/user-attachments/assets/7430fbf9-3b97-44f4-9a88-6db298b74379)



#### 软件架构  
平台采用前后端分离的架构设计，前端使用 Vue.js 构建动态用户界面，后端基于 Spring Boot 提供 API 服务，结合 MyBatis 实现高效的数据库操作。  

**系统模块**：  
1. **失物登记模块**：用户可上传物品信息（如描述、图片、拾取/丢失地点等）。  
2. **寻物启事模块**：用户可发布寻物需求，并查看相关物品的登记信息。  
3. **物品匹配模块**：系统根据登记信息，智能匹配可能的失物与拾物。  
4. **管理员模块**：管理员可审核物品信息，管理用户内容，确保信息真实有效。  

#### 安装教程  

1. 克隆项目到本地：  
   ```bash  
   git clone https://gitee.com/yourusername/lost-and-found-campus.git  
   ```  

2. 配置数据库：  
   在 MySQL 中创建数据库并导入初始数据文件 `init.sql`。  

3. 启动后端服务：  
   ```bash  
   cd backend  
   mvn clean install  
   mvn spring-boot:run  
   ```  

4. 启动前端服务：  
   ```bash  
   cd frontend  
   npm install  
   npm run serve  
   ```  

5. 在浏览器中访问 `http://localhost:8080` 即可使用系统。  

#### 使用说明  

1. **登记失物**：用户需登录系统并填写失物/拾物信息，包括物品描述、图片和地点等。  
2. **查看物品列表**：通过物品分类、地点等条件筛选相关信息。  
3. **物品匹配与联系**：查看匹配的物品信息并通过系统内联系方式与对方联系。  
4. **管理员功能**：审核用户提交的信息，并处理争议或异常内容。  

