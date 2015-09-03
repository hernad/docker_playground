# Docker runtime arguments

Example usage:

     docker build -t test-args .
     docker run test-args /start.sh 1 2 3


Output:

     bash-3.2$ docker run test-args /start.sh 1 2 3
     hello docker world
     Argumenti: 1, 2, 3


