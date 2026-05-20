root@dockerhost:~# history
    1  docker info
    2  docker search amazonlinux
    3  docker images
    4  docker ps -a
    5  docker rmi $(docker images -q)
    6  docker images
    7  docker rm $(docker ps -aq)
    8  docker rmi $(docker images -q)
    9  docker images
   10  docker ps -a
   11  docker info
   12  docker search amazonlinux
   13  docker pull amazonlinux
   14  docker images
   15  docker pull ubuntu
   16  docker images
   17  docker pull tomcat
   18  docker images
   19  docker run amazonlinux:latest
   20  docker ps -a
   21  ll
   22  ls
   23  docker run -it amazonlinux
   24  docker ps -a
   25  docker run -it --name cont1 amazonlinux
   26  docker ps -a
   27  docker run -it --name cont2 amazonlinux
   28  docker ps -a
   29  docker stop cont1
   30  docker ps -a
   31  docker rename affectionate_faraday cont3
   32  docker ps -a
   33  docker rename tender_jepsen cont3
   34  docker rename tender_jepsen cont4
   35  docker ps -a
   36  docker start cont1
   37  docker ps -a
   38  docker start cont3
   39  docker ps
   40  docker stop cont2
   41  docker pause cont1
   42  docker ps -a
   43  docker stop cont1
   44  docker ps -a
   45  docker pause cont3
   46  docker ps -a
   47  docker stop cont3
   48  docker start cont1 cont2
   49  docker ps -a
   50  docker rm cont4
   51  docker ps -a
   52  docker rm cont1
   53  docker rm -f cont1
   54  docker ps -a\
   55  docker pause cont3
   56  docker pause cont2
   57  docker ps -a
   58  docker unpause cont2
   59  docker ps -a
   60  docker attach cont2
   61  docker ps -a
   62  docker attach cont2
   63  docker ps -a
   64  docket start cont2
   65  docker start cont2
   66  docker ps -a
   67  docker exec -it cont2 /bin/bash
   68  docker ps -a
   69  docker images
   70  docker rmi ubuntu
   71  docker ps -a
   72  docker exec -it cont2 /bin/bash
   73  docker images
   74  docker ps -a
   75  docker start cont2
   76  docker ps -a
   77  docket attach cont2
   78  docker attach cont2
   79  docker ps -a
   80  docker start cont2
   81  docker exec -it cont2 /bin/bash
   82  docker ps -a
   83  docker images
   84  docker rmi tomcat:latest
   85  docker rmi amazonlinux:latest
   86  docker rmi amazonlinux:latest --force
   87  docker images
   88  docker ps -a
   89  docke exec -it cont2 /bin/bash
   90  docker exec -it cont2 /bin/bash
   91  docker ps -a
   92  git --version
   93  docker ps
   94  docker attach cont2
   95  docker run -it --name cont1 amazonlinux
   96  docker images
   97  docker commit cont2
   98  docker images
   99  docker images -a
  100  docker run -it --name cont5 226b8c9e9c39
  101  docker run -it --name cont6 226b8c9e9c39
  102  docker images -a
  103  docker tag 226b8c9e9c39 testimg:git
  104  docker images -a
  105  docker images
  106  docker ps -a
  107  docker rm -f cont6 cont2 cont1 cont3
  108  docker ps -a
  109  docker run -it --name cont6 testimg:git
  110  docker  ps
  111  docker commit cont6
  112  docker images
  113  docker images -a
  114  docker tag 21bfae6abae5 amazonlinux:git_java
  115  docker images -a
  116  docker run -it --name cont7 amazonlinux:git_java
  117  docker ps
  118  (docker ps -aq)
  119  docker rm -f $(docker ps -aq)
  120  docker ps -a
  121  docker images -q
  122  docker rmi $(docker images -q)
  123  docker images
