# jenkinsGopalakrishnan-gl
2021 Juan M. Fonseca-Solis. Notes for the course https://testautomationu.applitools.com/jenkins-tutorial/

## 1 Pre-requisites
* None

## 2 Project set-up
* None

## 3 Run
* None

## 4 Theory

### 4.1 Key concepts
* Continuous integration (CI): a development practice in which code changes are pushed often in a shared repository.
* Continuous deployment (CD): a software engineering approach hat uses automated deployments to build potential deliverables.
* Continuous delivery (CD?): basically, a CD where deliverables are also deployed.
* CI/CD provides higher confidence in the delivery process, better quality code, systematic versioning, and faster deliverables to the market. It also decreases the risk and cost, and facilitates the gathering of quality metrics.

### 4.2. Jenkins
* Alternatives: Team city, Jenkins, Travis CI, Bamboo, Buddy, and Circle CI.
* Jenkins is open source, cross-platform, extendable using plugins, and allows to build/deploy code.
* Jenkins works in a outdated and scary master-slave architecture. Master pulls the code from the repository, assigns jobs to the slaves and monitors their progress. Slaves are remote machines (or Docker containers?).
### 4.3 Installations
* Pre-requisites: java, Jenkins's war file.
* Execution: `java -jar jenkins.war --httpPort:8080` (if started for the first time, a username/password is provided).





