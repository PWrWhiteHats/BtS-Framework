[![Build Status](https://travis-ci.org/PWrWhiteHats/BtS-Framework.svg?branch=master)](https://travis-ci.org/PWrWhiteHats/BtS-Framework)
[![codecov](https://codecov.io/gh/PWrWhiteHats/BtS-Framework/branch/master/graph/badge.svg)](https://codecov.io/gh/PWrWhiteHats/BtS-Framework)
# BtS-Framework

Official framework for Break The Syntax CTF - based on [CTFd](https://github.com/CTFd/CTFd)

# Credits

All original credits are listed on official [CTFd repository](https://github.com/CTFd/CTFd#credits)

# Development

People involved in development of this repository:

- [Arqsz](https://github.com/TheArqsz)
- [TomBombadil](https://github.com/TomasBombadil)

# Environment

Most of important enviromental variables must be included in **.env** file. Example [here](example.env)

# Prerequisites

If you want use the Framework and monitoring from this repository you need to create shared network:
```
    docker network create monitoring-shared-network
```
When this step is completed, you need to use [docker-compose-monitoring.yml](docker-compose-monitoring.yml) instead of [docker-compose.yml](docker-compose.yml)

# Version

Based on [CTFd](https://github.com/CTFd/CTFd) version 2.2.3