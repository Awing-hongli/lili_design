### 步骤如下：

### 1️⃣ 安装 JDK（Maven 需要 Java 环境）

1. 下载 JDK：https://www.oracle.com/java/technologies/javase-downloads.html
或使用开源版本：https://adoptium.net/
2. 安装完成后，配置环境变量：
    - 设置 `JAVA_HOME` 指向 JDK 安装路径（如 `C:\\Program Files\\Java\\jdk-17`）。
    - 在 `Path` 中添加：`%JAVA_HOME%\\bin`
3. 打开命令提示符验证：
    
    ```bash
    java -version
    
    ```
    

---

### 2️⃣ 下载和配置 Maven

1. 下载 Maven：
官网：https://maven.apache.org/download.cgi
    
    选择 Binary zip 包版本。
    
2. 解压：
解压到某个路径，比如：`C:\\Tools\\apache-maven-3.9.6`
3. 配置环境变量：
    - 新建 `MAVEN_HOME`，指向 Maven 目录（如：`C:\\Tools\\apache-maven-3.9.6`）。
    - 编辑系统变量 `Path`，添加：`%MAVEN_HOME%\\bin`
4. 验证是否安装成功：
打开命令行，输入：
    
    ```bash
    mvn -v
    
    ```
    
    正常输出 Maven 版本信息表示安装成功。
