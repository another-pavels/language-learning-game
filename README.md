# Numbers Repetition Game TEST

A simple language learning game as a demonstration of a basic React/Redux app.

[Demo](http://ec2-35-160-149-202.us-west-2.compute.amazonaws.com)

## Getting Started

```sh
git clone https://github.com/maleksan/language-learning-game.git
cd language-game
npm install
npm run build
npm start
```

## Docker stuff

```sh
#
docker build -t fitamaksims/language-learning-game-server:0.0.1 .
#
docker container run --rm -p 8080:8080 fitamaksims/language-learning-game-server:0.0.1
#
docker push fitamaksims/language-learning-game-server:0.0.1
```

## Attribution

under an [Attribution 3.0](https://creativecommons.org/licenses/by/3.0/us/legalcode) license
