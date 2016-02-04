FROM jenkins:1.642.1

RUN echo "ws-cleanup:0.28" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "timestamper:1.7.2" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "rebuild:1.25" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "dropdown-viewstabbar-plugin:1.7" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "build-timeout:1.15" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "copyartifact:1.37" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "build-pipeline-plugin:1.4.9" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "envinject:1.92.1" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "credentials:1.21" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "git:2.4.0" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "git-client:1.19.0" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "scm-api:0.2" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "rebuild:1.25" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "jobConfigHistory:2.12" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "plugin-usage-plugin:0.3" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "credentials:1.23" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "groovy:1.27" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "job-dsl:1.40" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "github-api:1.69" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "github:1.13.3" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "plain-credentials:1.1" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "cloudbees-credentials:3.3" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "config-file-provider:2.9.3" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "token-macro:1.5.1" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "clone-workspace-scm:0.6" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "chucknorris:0.5" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "xvfb:1.0.16" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "parameterized-trigger:2.30" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt
RUN echo "jquery:1.11.2-0" > /var/jenkins_home/plugins.txt; /usr/local/bin/plugins.sh /var/jenkins_home/plugins.txt

############################################
# Configure Jenkins
############################################
# Jenkins settings
COPY config/config.xml /usr/share/jenkins/ref/config.xml

# Jenkins Settings, i.e. Maven, Groovy, ...
COPY config/hudson.tasks.Maven.xml /usr/share/jenkins/ref/hudson.tasks.Maven.xml
