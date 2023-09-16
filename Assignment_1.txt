 6  sudo addgroup one
    7  sudo adduser apple -gid 1001
    8  ls
    9  cat /etc/group
   10  cat etc/passwd
   11  cat /etc/passwd
   12  sudo adduser banana -gid 1001
   13  sudo adduser cat -gid 1001
   14  sudo adduser dog -gid 1001
   15  cd
   16  pwd
   17  cd
   18  cd ..
   19  cd
   20  ls
   21  cd ..
   22  sudo adduser elephant -gid 1001 -y
   23  sudo adduser elephant -gid 1001 
   24  sudo addgroup two
   25  sudo adduser fish -gid 1002
   26  sudo adduser gun -gid 1002
   27  sudo adduser kitkat -gid 1002
   28  sudo adduser lolipop -gid 1002
   29  sudo adduser marshmallo -gid 1002
   30  sudo addgroup three
   31  sudo adduser jelly -gid 1003
   32  sudo adduser horse -gid 1003
   33  sudo adduser icecream -gid 1003
   34  sudo addgroup four 
   35  sudo adduser new -gid 1004
   36  sudo adduser oppo -gid 1004
   37  sudo adduser vivo -gid 1004
   38  sudo adduser china -gid 1004
   39  ls -l
   40  sudo chgroup horse -G two
   41  sudo chgrp horse -G two
   42  sudo usermod chgrp horse -G two
   43  sudo chgrp horse 
   44  sudo usermod chgrp horse -g two
   45  sudo usermod horse -g two
   46  ls -l
   47  sudo usermod  icecream -g two
   48  ls -l
   49  sudo usermod  kitkat -g three
   50  ls -l
   51  sudo usermod  lolipop -g three
   52  sudo usermod  marshmallo -g three
   53  ls -l
   54  whoami
   55  sudo mkdir everyone
   56  sudo chmod 777 everyone
   57  ls -l
   58  su apple
   59  whoami
   60  su banana
   61  exit
   62  ls
   63  ls -l
   64  clear
   65  cd ..
   66  sudo -s
   67  ls
   68  everyone
   69  cd everyone
   70  ls-l
   71  ls
   72  ls -l
   73  sudo usermod oppo -g one
   74  ls
   75  cd ..
   76  ls -l
   77  sudo usermod vivo -g two
   78  cd ..
   79  ls -l
   80  cd /home
   81  ls -l
   82  sudo usermod jelly , kitkat, lolipop, marshmallo -G sudo  
   83  sudo usermod jelly -G sudo  
   84  sudo usermod kitkat -G sudo  
   85  sudo usermod lolipop -G sudo  
   86  sudo usermod marshmallo -G sudo  
   87  sudo usermod fish -G one
   88  sudo usermod gun -G one
   89  tail cat etc/group
   90  tac etc/group