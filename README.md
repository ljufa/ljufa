# 👋 Hello there! I am Dragan.
 
### 👨🏼‍💻&nbsp;About Me

💡 &nbsp; I'm a freelance __Sr. Software Engineer/Developer__ with professional experience in the design and development of backend applications in Java and Kotlin. 

🚀 &nbsp; I am interested in building reliable and scalable distributed systems, automation, event sourcing architectures, domain-driven design...

🌱 &nbsp; Currently I'm learning Rust programming language.

✍️ &nbsp; In my free time, I enjoy making DIY audio electronics and programming microcontrollers.

📄 &nbsp; You can check my [Resume](https://drive.google.com) for more details about work experience.

### 🛠 &nbsp;Tech Stack
|||
----:|----
Programing languages:|<img alt="Java" src="assets/java.svg" width=35px>&nbsp;&nbsp;<img alt="Kotlin" src="assets/kotlin.svg" width=35px>&nbsp;&nbsp;<img alt="Rust" src="assets/rust.svg" width=35px>&nbsp;&nbsp;<img alt="Go" src="assets/go.svg" width=35px>
Tools & Frameworks:|<img alt="Spring" src="assets/spring.svg" width=35px>&nbsp;&nbsp;<img alt="Spring Boot" src="assets/springboot.svg" width=35px>&nbsp;&nbsp;<img alt="Gradle" src="assets/gradle.svg" width=35px>&nbsp;&nbsp;<img alt="Swagger" src="assets/swagger.svg" width=35px>&nbsp;&nbsp;<img alt="Prometheus" src="assets/prometheus.svg" width=35px>&nbsp;&nbsp;<img alt="Grafana" src="assets/grafana.svg" width=35px>&nbsp;&nbsp;<img alt="Newrelic" src="assets/newrelic.svg" width=35px>
Cloud Technologies:|<img alt="Kubernetes" src="assets/kubernetes.svg" width=35px>&nbsp;&nbsp;<img alt="Docker" src="assets/docker.svg" width=35px>&nbsp;&nbsp;<img alt="Helm" src="assets/helm.svg" width=35px>&nbsp;&nbsp;<img alt="Azure" src="assets/microsoftazure.svg" width=35px>&nbsp;&nbsp;<img alt="Google Cloud" src="assets/googlecloud.svg" width=35px>
IDE, SCM & CI/CD:|<img alt="VSCode" src="assets/visualstudiocode.svg" width=35px>  &nbsp;&nbsp;<img alt="IntelliJ Idea" src="assets/intellijidea.svg" width=35px>&nbsp;&nbsp;<img alt="GitLab" src="assets/gitlab.svg" width=35px>&nbsp;&nbsp;<img alt="Github" src="assets/github.svg" width=35px>&nbsp;&nbsp;<img alt="TravisCI" src="assets/travisci.svg" width=35px>&nbsp;&nbsp;<img alt="TravisCI" src="assets/githubactions.svg" width=35px>
Messaging & DB:|<img alt="Apache Kafka" src="assets/apachekafka.svg" width=35px>&nbsp;&nbsp;<img alt="PostgreSQL" src="assets/postgresql.svg" width=35px>&nbsp;&nbsp;<img alt="MongoDB" src="assets/mongodb.svg" width=35px>&nbsp;&nbsp;<img alt="Redis" src="assets/redis.svg" width=35px>


## 🔥 My Github projects: 
## `top-tweets` (java, kotlin)
This application consumes Twitter filtered stream API, publishes tweets to Kafka topic, backend service consume messages from the topic, sort them using top K algorithm and exposes sorted list by GRPC API to the UI service. 
- [Tweets Stream Colector ▪️ top-tweets-stream-collector](https://github.com/ljufa/top-tweets-stream-collector)
- [Backend ▪️ top-tweets-backend](https://github.com/ljufa/top-tweets-backend)
- [UI ▪️ top-tweets-web](https://github.com/ljufa/top-tweets-web)
- [Deployment ▪️ top-tweets-deployment](https://github.com/ljufa/top-tweets-deployment)


## `dplayer` (rust)
Controller for DIY Raspberry PI 4 based audiophile streamer. It acts as a software controller for DAC chip AK4497 using the I2C protocol. It also implements a function to switch between different players: Music Player Daemon, Logitech Media Server, and Spotify. For each of the players, it implements base functions: Play, Stop, Next, and Prev. All the functions are exposed over IR remote interface and REST API consumed by the UI which is also written in rust wasm using [seed framework](https://seed-rs.org/). It can also print current player information on the LCD.

- [Backend ▪️ dplayer](https://github.com/ljufa/dplayer)
- [UI ▪️ dplayer-ui](https://github.com/ljufa/dplayer-ui)
- [Streamer Hardware & schematics ▪️ kicad](https://github.com/ljufa/kicad)

## `pvcexec` (go)
A simple Kubernetes tool that creates a temporary pod in your cluster with mounted two persistent volume claims so you can easily access data on them using commons Linux tools.
- [Binary ▪️ pvcexec](https://github.com/kubextender/pvcexec)
- [ZSH Docker Image ▪️ pvcexec-docker-zsh](https://github.com/kubextender/pvcexec-docker-zsh)
- [MC Docker Image ▪️ pvcexec-docker-mc](https://github.com/kubextender/pvcexec-docker-mc)

## `Arduino`
Random Arduino sketches, mainly for Attiny85
- [My Sketches](https://github.com/ljufa/arduino)


![Top Langs](https://github-readme-stats.vercel.app/api?username=ljufa&show_icons=true)![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ljufa)
