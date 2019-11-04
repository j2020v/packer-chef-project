# Intro to Packer-Json

Optional: Command line aligned with AWS CLI

Step by Step guide to building AMIs:

1. Install packer

  - https://www.packer.io/intro/getting-started/install.html


2. Need the app repo and Berkshelf

  - Berkshelf is a dependency manager for Chef cookbooks. Basically like your metadata file.


3. Need working repo for MongoDB and Nodejs locally
  - Ensure the Github repo works and passes all tests and add to Berksfile with this syntax for instance:

  ```
  cookbook 'node', git: 'git@github.com:j2020v/chef-nginx-cookbook.git'
```
4. Created .json packer file  

 - Template for .json file can be found in this link https://www.packer.io/intro/getting-started/build-image.html


5. Echo keys in .bash_profile (ACCESS KEY AND SECRET)


6. Describe variables and what infrastructure it is meant to use


7. Export variables  


8. Built AMIs externally and carried out provisions after
