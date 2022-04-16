# Continuous Documentation Project

!!! abstract "Learning Objectives"

    - [x] create a site for presentation of project documentation
    - [x] enable continuous integration and continuous deployment
    - [ ] support integration of external documentation for external project repositories
    - [x] ensure local development process is streamlined

!!! info "Technologies Used"

    === "architecture"

        - [x] mkdocs material static sites for feature rich documentation from markdown
        - [x] git, github and pages for free robust hosting
        - [ ] cloudflare to enhance security and edge cache for improved performance and data locality [production env]
        - [x] design for stateless and ephemeral deployments to improve security posture  
        - [x] use static site generation to enable effective cache utilization

    === "docker"

        - [x] use containers for local development to reduce dependencies
        - [x] volume mounts for mapping local file system to support auto-refresh on save capability
        - [x] docker-compose to streamline on-boarding

    === "github pages"

        - [x] free hosting that can be used with external domains
        - [x] integrates easily with github actions for CICD

    === "github actions"

        - [x] experimental repo created to support testing of new capabilities and experimental trials
        - [x] actions created to support CICD process for the site
