# VUE内容管理系统

**此项目已完成从 Vue2 到 Vue3 的重构。**

这是一个基于 `Vue3` 和 `Vuetify` 的内容管理系统。用户可以查看文章列表、查看文章详情、添加/编辑/删除文章，并将文章分配到不同的分类中。同时支持管理员管理与权限分配功能。  
<br/><br/>
Demo: <a href="https://vue-vuetify-blog-system.vercel.app/">https://vue-vuetify-blog-system.vercel.app</a>

## 特点

- **文章列表展示**：获取并展示文章数据。
- **文章详情查看**：点击文章标题可查看该文章的详细内容。
- **加载状态指示**：在数据获取过程中显示加载指示器，为用户提供更好的体验。
- **文章增删改查**：支持文章的增、改、删操作。
- **分类管理**：支持分类的添加、编辑、删除，并可将文章分配到不同的分类中。
- **管理员管理**：对管理员进行增、改、删操作。
- **权限分配**：为每位管理员分配不同权限，管理系统内的角色与操作权限。
- **响应式UI**：使用 `Vuetify` 的现代化 UI 组件，提供响应式设计。

## 截图

<img src="./screenshot/1.png" width="400"/><br/>
<img src="./screenshot/6.png" width="700"/><br/><br/>
<img src="./screenshot/2.png" width="500"/><br/><br/>
<img src="./screenshot/3.png" width="500"/><br/><br/>
<img src="./screenshot/4.png" width="500"/><br/><br/>
<img src="./screenshot/5.png" width="500"/><br/>

## 技术栈

- **Vue 3**：前端框架，用于构建用户界面。
- **Vuetify**：Vue 的 UI 组件库，提供现代化 UI 设计。
- **JavaScript (ES6)**：实现项目逻辑的编程语言。
- **HTML5 & CSS3**：基础的页面结构和样式设计。

## 功能介绍

1. **文章列表**：
   - 获取并显示所有文章列表。
   - 点击文章标题可进入文章详情页面。
   - 可根据不同分类对文章进行过滤。
   - 数据加载中显示加载指示器。

2. **文章详情**：
   - 显示文章的标题和内容。
   - 若文章不存在则显示错误信息。
   - 支持文章的添加、编辑、删除，即 CRUD 操作。

3. **分类管理**：
   - 显示分类列表，并可对分类进行添加、编辑、删除操作。
   - 支持将文章分配到不同分类中，并管理各分类下的文章。

4. **管理员管理**：
   - 显示管理员列表，并可添加、编辑、删除管理员。
   - 管理员可根据自身权限访问系统的不同部分。

5. **权限分配**：
   - 系统管理员可为各管理员分配不同的角色或权限。
   - 基于权限的访问和操作控制，确保系统安全和有序运转。

## 使用说明

### 开发环境搭建

1. 安装依赖：

   ```bash
   npm install
   ```

2. 启动开发服务器：

   ```bash
   npm run dev
   ```

3. 在浏览器中访问：

   ``` 
   http://localhost:5173
   ```

### 文章与分类管理使用说明

- **文章管理**：可对文章进行添加、编辑、删除操作，并将文章分配到特定分类下。管理员也可将文章在不同分类之间自由移动。
- **分类管理**：可对分类进行添加、编辑、删除操作，并对每个分类下的文章进行管理。

### 管理员管理功能

本项目提供对管理员进行权限分配的管理功能。根据管理员的权限，可对文章、分类及其他管理员进行管理。通过为管理员分配如「系统管理员」「文章管理员」等角色权限，可以确保系统的安全性与有序运行。

## 后续改进方向

- 丰富管理员的细粒度权限配置功能。
- 增加用户认证及安全功能。
- 增强复杂的过滤与搜索功能。