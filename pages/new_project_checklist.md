# New Project Checklist


### Day 0

- [ ] Tech stack decisions have been made
  - [ ] Source Control
  - [ ] Frontend
  - [ ] Backend
  - [ ] Storage/Persistence
  - [ ] Cloud provider
  - [ ] Authentication (User registration and sign in flows)
- [ ] Tech stack decisions must to support the following use-cases
  - [ ] Zero-downtime deployments (Blue/Green, Rolling, Canary)
  - [ ] IaC-compatible
  - [ ] Easy Rollbacks
  - [ ] Containerization
- [ ] Additional recommendations are formulated based on tech stack decisions
  - [ ] Logging aggregation
  - [ ] Application Performance Monitoring too
  - [ ] Infrastructure Performance Monitoring tool
  - [ ] Alerting strategy

### Day 1

- [ ] Hello World full-stack app is set up to run locally. This includes connections from frontend -> backend -> DB

### Week 1

- [ ] Sample unit test, integration test, and e2e test is set up
- [ ] Dev environment is set up and fully accessible
- [ ] Code formatting/linting in place
- [ ] Users can sign in to the application
  - [ ] This includes standard workflows such as registration, password reset, etc.
- [ ] Continuous Integration pipeline is running and and allows deployments to the Dev environment
  - [ ] Tests are running in CI

### Week 2

- [ ] Dev environment is deployed with an Infrastructure as Code tool to enable repeatable environment builds (avoid ClickOps!)
- [ ] IaC is leveraged to deploy both a Staging and Production environment
- [ ] CI pipeline allows promotion of builds from Dev to Staging and Production
- [ ] Additional considerations for production are implemented
- [ ] Zero-Downtime deployment is fully enabled (Blue/Green, Rolling, Canary)
- [ ] Logging aggregation is fully functional

 
### Month 1

- [ ] Easy-to-view alerts are received when app is down
- [ ] Test coverage is solid enough that the need for manual QA is minimized
- [ ] Changes can be confidently deployed to production
- [ ] We have a plan for load-testing in place