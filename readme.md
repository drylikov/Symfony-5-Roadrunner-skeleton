# Symfony 5 + Roadrunner skeleton

![build](https://github.com/DenSul/symfony-roadrunner-skeleton/workflows/build/badge.svg?branch=master)

It's my skeleton project.

## Includes:
- docker
- Roadrunner
- Github actions:
  - PHPStan
  - Magic numbers
  - PHP-CS
  - Composer validate
  - Run tests (*WIP*)

Commit message: `[SKIP CI] ...` disabled build app and run tests.


## Getting Started

Just fork/clone this repository and start work!


### Installing

Just `dev-compose up -d`

WEB:
```
http://127.0.0.1:9001
https://127.0.0.1:9002
```
Redis:
```
127.0.0.1:4004
```
PostgreSQL:
```
127.0.0.1:4005
```

## Running the tests or other job.

```bash
# Fix code style
./bin/task check-code-style

# Validate composer configuration
./bin/task check-composer

# Validate no magic numbers
./bin/task check-magic-numbers

# PHPStan. Run locally
./bin/task phpstan
```

Just check [Taskfile.yml](./Taskfile.md).


## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/densul/symfony-roadrunner-skeleton/tags). 
And check [CHANGELOG.yml](./CHANGELOG.md).
