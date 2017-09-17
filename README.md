# docker-hubot

[DockerHub blue1st/hubot](https://hub.docker.com/r/blue1st/hubot/)


## Usage

### Create Project

```bash
$ docker run -it -v $PWD:/hubot blue1st/hubot yo hubot
? ==========================================================================
We're constantly looking for ways to make yo better!
May we anonymously report usage statistics to improve the tool over time?
More info: https://github.com/yeoman/insight & http://yeoman.io
========================================================================== Yes
                     _____________________________
                    /                             \
   //\              |      Extracting input for    |
  ////\    _____    |   self-replication process   |
 //////\  /_____\   \                             /
 ======= |[^_/\_]|   /----------------------------
  |   | _|___@@__|__
  +===+/  ///     \_\
   | |_\ /// HUBOT/\\
   |___/\//      /  \\
         \      /   +---+
          \____/    |   |
           | //|    +===+
            \//      |xx|

? Owner (User <user@example.com>)
```

### Run Hubot

```bash
$ docker run -v $PWD:/hubot blue1st/hubot bin/hubot
```
