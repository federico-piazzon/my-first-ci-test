# My First CI Test
My Continuous Integration Test with Travis and Circle CI

## All Steps

1. create repository X on github
2. login with github on travis.org/circleci.com
3. enable travis/circleci build on the X repository
4. create code directory on my pc
5. to build Travis CI need a .travis.yml/ Circle CI need a .circleci/config.yml, so create on previous directory
6. build is a simple script, for example run test with phpunit
7. create the test to run 
8. phpunit must be installed to run this test, so create a composer.json
9. update .travis.yml to run "composer install" before build
10. commit and wait travis/circleci for build result