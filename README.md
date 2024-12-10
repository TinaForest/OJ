### **OJ — YhyOJ System**

#### **System Features**

1. User Module
   - Register
   - Login
2. Problem Module
   - Create problems (admin)
   - Delete problems (admin)
   - Edit problems (admin)
   - Search problems (user)
   - Solve problems online (problem details page)
3. Judging Module
   - Submit answers for evaluation (correct or incorrect results)
   - Handle errors (e.g., memory overflow, security, timeouts)
   - **Code Sandbox**: Provides a secure environment for code execution
   - Open APIs

#### **Technologies Used**

- Frontend
  - Vue 3
  - Arco Design component library
  - Custom project templates
  - Online code and document editors
- Backend
  - Java process management
  - Java Security Manager
  - Some JVM concepts
- Server
  - Virtual machines (cloud servers)
  - Docker (for code sandbox implementation)
  - Spring Cloud microservices, message queues, and design patterns

------

### **Frontend Details**

#### **Structure** (under the `src` folder):

1. **assets**: Static resources like images, fonts, and styles.
2. **components**: Reusable components like UI elements and widgets.
3. **layouts**: Application layouts or page templates.
4. **router**: Manages navigation and URL routes.
5. **store**: State management code for global data handling.
6. **views**: Contains the different pages of the application, each corresponding to a route.
7. **access**: Handles global access control.

#### **Initialization**:

1. Ensure a proper Node.js environment and Vue CLI.

2. Create the frontend project: `vue create yhyoj_frontend`.

3. Install Arco Design component library:

   ```
   yarn add --dev @arco-design/web-vue
   ```

4. Set up global entry point in `App.vue`.

------

### **Backend**

The document provides an overview of backend features but does not delve into details here.

------

### **Code Sandbox**

Highlights the implementation of secure environments for code execution using Docker.