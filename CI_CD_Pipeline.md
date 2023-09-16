# JENKINS

Jenkins is a Continous Integration tool that allows continous development, test and deployment of newly created tools. It is an open source automation server writeen in Java. It is used to automate software development process via continous integration and facilities continous delivery.

## Jenkins Architecture

At any time, the developer can pull a code they have to work on from a repository and after commiting the changes, they can submit the code back to a Continous Integration Server, it then goes ahead to the tester and tester validates it on the basis of some tests, if the build passes, it goes ahead and if it fails, it goes back to the developer for changes and correction.

## Features of Jenkins

1. Easy Installation ---> self-contained java-program, ready to run with packages
2. Easy Configuration ---> easy set-up that includes error checks
3. Plugins ---> has many plugins and integrates with CI/CD toolchain
4. Extensible ---> can be extended by its plugin architecture
5. Distributed ---> can easily distribute work across multiple machines

## Jenkins Pipeline

Development takes place at first and then CI/CD performs its tasks -

1. Code Commit
2. Build
3. Test
4. Release
5. Deploy/Deliver

Production takes place in the end.

# CI/CD Pipeline using Jenkins

1. Dev Env ---> project develop
2. Q.A. ---> Quality assesment env, testing env
3. UAT Env ---> User acceptance testing
4. Pilot Env(Pre production Env) ---> performance test
5. Production Env ---> Live

## CI/CD

Continous Integration ---> build+test+deploy

Continous Delivery/Deployment ---> release+build+deploy
