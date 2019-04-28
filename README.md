# awx-getting-started

## Docker Security
Docker offers the Docker Bench for Security script (https://github.com/docker/docker-bench-security) , which checks a Docker configuration against the published hardening guide: CIS DOCKER 1.12.0 BENCHMARK V1.0.0 (link). 
You can just download the script and run it straight from your host. Once you have run the script, you will be presented the output shown below:


The script results in Info, Warning, and Pass notes for each of the recommendations which are grouped into 5 sections:
Host Configuration
Docker Daemon Configuration
Docker Daemon Configuration Files
Container Images and Build Files
Container Runtime

Once the reported is generated, you can follow the mentioned benchmark document to remediate them.
