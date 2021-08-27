# linux

## ubuntu

### os-release
```bash
root@0734b09f8a77:/bin# cat /etc/os-release
NAME="Ubuntu"
VERSION="20.04.2 LTS (Focal Fossa)"
ID=ubuntu
ID_LIKE=debian
PRETTY_NAME="Ubuntu 20.04.2 LTS"
VERSION_ID="20.04"
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
VERSION_CODENAME=focal
UBUNTU_CODENAME=focal
```

### default commands

```bash
root@0734b09f8a77:/bin# ll -a
total 22956
drwxr-xr-x.  2 root root      8192 Jul 23 17:38  ./
drwxr-xr-x. 13 root root       145 Jul 23 17:35  ../
-rwxr-xr-x.  1 root root     59736 Sep  5  2019 '['*
-rwxr-xr-x.  1 root root     30952 Jul 21  2020  addpart*
-rwxr-xr-x.  1 root root     18824 Jun 15 11:05  apt*
-rwxr-xr-x.  1 root root     88536 Jun 15 11:05  apt-cache*
-rwxr-xr-x.  1 root root     31192 Jun 15 11:05  apt-cdrom*
-rwxr-xr-x.  1 root root     27016 Jun 15 11:05  apt-config*
-rwxr-xr-x.  1 root root     47576 Jun 15 11:05  apt-get*
-rwxr-xr-x.  1 root root     27931 Jun 15 11:05  apt-key*
-rwxr-xr-x.  1 root root     63960 Jun 15 11:05  apt-mark*
-rwxr-xr-x.  1 root root     39288 Sep  5  2019  arch*
lrwxrwxrwx.  1 root root        21 Jul 23 17:35  awk -> /etc/alternatives/awk*
-rwxr-xr-x.  1 root root     59768 Sep  5  2019  b2sum*
-rwxr-xr-x.  1 root root     43352 Sep  5  2019  base32*
-rwxr-xr-x.  1 root root     43352 Sep  5  2019  base64*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  basename*
-rwxr-xr-x.  1 root root   1183448 Jun 18  2020  bash*
-rwxr-xr-x.  1 root root      6794 Jun 18  2020  bashbug*
-rwxr-xr-x.  3 root root     39144 Sep  5  2019  bunzip2*
-rwxr-xr-x.  3 root root     39144 Sep  5  2019  bzcat*
lrwxrwxrwx.  1 root root         6 Sep  5  2019  bzcmp -> bzdiff*
-rwxr-xr-x.  1 root root      2227 Sep  5  2019  bzdiff*
lrwxrwxrwx.  1 root root         6 Sep  5  2019  bzegrep -> bzgrep*
-rwxr-xr-x.  1 root root      4877 Sep  4  2019  bzexe*
lrwxrwxrwx.  1 root root         6 Sep  5  2019  bzfgrep -> bzgrep*
-rwxr-xr-x.  1 root root      3775 Sep  5  2019  bzgrep*
-rwxr-xr-x.  3 root root     39144 Sep  5  2019  bzip2*
-rwxr-xr-x.  1 root root     18584 Sep  5  2019  bzip2recover*
lrwxrwxrwx.  1 root root         6 Sep  5  2019  bzless -> bzmore*
-rwxr-xr-x.  1 root root      1297 Sep  5  2019  bzmore*
lrwxrwxrwx.  1 root root         3 Feb 26  2020  captoinfo -> tic*
-rwxr-xr-x.  1 root root     43416 Sep  5  2019  cat*
-rwxr-xr-x.  1 root root      3330 Dec 16  2020  catchsegv*
-rwxr-sr-x.  1 root shadow   84512 May 28  2020  chage*
-rwxr-xr-x.  1 root root     14656 Feb 14  2020  chattr*
-rwxr-xr-x.  1 root root     72024 Sep  5  2019  chcon*
-rwsr-xr-x.  1 root root     85064 May 28  2020  chfn*
-rwxr-xr-x.  1 root root     72024 Sep  5  2019  chgrp*
-rwxr-xr-x.  1 root root     63864 Sep  5  2019  chmod*
-rwxr-xr-x.  1 root root     51432 Jul 21  2020  choom*
-rwxr-xr-x.  1 root root     72024 Sep  5  2019  chown*
-rwxr-xr-x.  1 root root     39144 Jul 21  2020  chrt*
-rwsr-xr-x.  1 root root     53040 May 28  2020  chsh*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  cksum*
-rwxr-xr-x.  1 root root     14656 Feb 26  2020  clear*
-rwxr-xr-x.  1 root root     14568 Jun 18  2020  clear_console*
-rwxr-xr-x.  1 root root     51296 Apr  8  2019  cmp*
-rwxr-xr-x.  1 root root     43384 Sep  5  2019  comm*
-rwxr-xr-x.  1 root root    153976 Sep  5  2019  cp*
-rwxr-xr-x.  1 root root     55672 Sep  5  2019  csplit*
-rwxr-xr-x.  1 root root     47480 Sep  5  2019  cut*
-rwxr-xr-x.  1 root root    129816 Jul 18  2019  dash*
-rwxr-xr-x.  1 root root    108920 Sep  5  2019  date*
-rwxr-xr-x.  1 root root     80256 Sep  5  2019  dd*
-rwxr-xr-x.  1 root root     21328 Jun 21  2019  deb-systemd-helper*
-rwxr-xr-x.  1 root root      4430 Jun 21  2019  deb-systemd-invoke*
-rwxr-xr-x.  1 root root      2859 Aug  3  2019  debconf*
-rwxr-xr-x.  1 root root     11541 Aug  3  2019  debconf-apt-progress*
-rwxr-xr-x.  1 root root       608 Aug  3  2019  debconf-communicate*
-rwxr-xr-x.  1 root root      1719 Aug  3  2019  debconf-copydb*
-rwxr-xr-x.  1 root root       647 Aug  3  2019  debconf-escape*
-rwxr-xr-x.  1 root root      2935 Aug  3  2019  debconf-set-selections*
-rwxr-xr-x.  1 root root      1827 Aug  3  2019  debconf-show*
-rwxr-xr-x.  1 root root     30952 Jul 21  2020  delpart*
-rwxr-xr-x.  1 root root     93128 Sep  5  2019  df*
-rwxr-xr-x.  1 root root    219480 Apr  8  2019  diff*
-rwxr-xr-x.  1 root root     67800 Apr  8  2019  diff3*
-rwxr-xr-x.  1 root root    142144 Sep  5  2019  dir*
-rwxr-xr-x.  1 root root     47456 Sep  5  2019  dircolors*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  dirname*
-rwxr-xr-x.  1 root root     84440 Jul 21  2020  dmesg*
lrwxrwxrwx.  1 root root         8 Nov  7  2019  dnsdomainname -> hostname*
lrwxrwxrwx.  1 root root         8 Nov  7  2019  domainname -> hostname*
-rwxr-xr-x.  1 root root    309944 Mar 23  2020  dpkg*
-rwxr-xr-x.  1 root root    178728 Mar 23  2020  dpkg-deb*
-rwxr-xr-x.  1 root root    154208 Mar 23  2020  dpkg-divert*
-rwxr-xr-x.  1 root root     20514 Mar 23  2020  dpkg-maintscript-helper*
-rwxr-xr-x.  1 root root    166488 Mar 23  2020  dpkg-query*
-rwxr-xr-x.  1 root root    125424 Mar 23  2020  dpkg-split*
-rwxr-xr-x.  1 root root     63760 Mar 23  2020  dpkg-statoverride*
-rwxr-xr-x.  1 root root     84472 Mar 23  2020  dpkg-trigger*
-rwxr-xr-x.  1 root root    108920 Sep  5  2019  du*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  echo*
-rwxr-xr-x.  1 root root        28 Jan 29  2020  egrep*
-rwxr-xr-x.  1 root root     43352 Sep  5  2019  env*
-rwxr-xr-x.  1 root root     43384 Sep  5  2019  expand*
-rwxr-sr-x.  1 root shadow   31312 May 28  2020  expiry*
-rwxr-xr-x.  1 root root     55640 Sep  5  2019  expr*
-rwxr-xr-x.  1 root root     80248 Sep  5  2019  factor*
-rwxr-xr-x.  1 root root     23136 May 28  2020  faillog*
-rwxr-xr-x.  1 root root     35048 Jul 21  2020  fallocate*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  false*
-rwxr-xr-x.  1 root root        28 Jan 29  2020  fgrep*
-rwxr-xr-x.  1 root root     35096 Jul 21  2020  fincore*
-rwxr-xr-x.  1 root root    320160 Feb 18  2020  find*
-rwxr-xr-x.  1 root root     73128 Jul 21  2020  findmnt*
-rwxr-xr-x.  1 root root     35128 Jul 21  2020  flock*
-rwxr-xr-x.  1 root root     47448 Sep  5  2019  fmt*
-rwxr-xr-x.  1 root root     43352 Sep  5  2019  fold*
-rwxr-xr-x.  1 root root     26864 May 28 17:27  free*
-rwxr-xr-x.  1 root root     35112 Dec 16  2020  getconf*
-rwxr-xr-x.  1 root root     39576 Dec 16  2020  getent*
-rwxr-xr-x.  1 root root     22760 Jul 21  2020  getopt*
-rwsr-xr-x.  1 root root     88464 May 28  2020  gpasswd*
-rwxr-xr-x.  1 root root    457880 Jan  6  2021  gpgv*
-rwxr-xr-x.  1 root root    199136 Jan 29  2020  grep*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  groups*
-rwxr-xr-x.  2 root root      2346 Dec 13  2019  gunzip*
-rwxr-xr-x.  1 root root      6376 Dec 13  2019  gzexe*
-rwxr-xr-x.  1 root root     97496 Dec 13  2019  gzip*
-rwxr-xr-x.  1 root root     47480 Sep  5  2019  head*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  hostid*
-rwxr-xr-x.  1 root root     26856 Nov  7  2019  hostname*
lrwxrwxrwx.  1 root root         7 Jul 21  2020  i386 -> setarch*
-rwxr-xr-x.  1 root root     68000 Dec 16  2020  iconv*
-rwxr-xr-x.  1 root root     47480 Sep  5  2019  id*
-rwxr-xr-x.  1 root root     63880 Feb 26  2020  infocmp*
lrwxrwxrwx.  1 root root         3 Feb 26  2020  infotocap -> tic*
-rwxr-xr-x.  1 root root    158112 Sep  5  2019  install*
-rwxr-xr-x.  1 root root     30952 Jul 21  2020  ionice*
-rwxr-xr-x.  1 root root     35120 Jul 21  2020  ipcmk*
-rwxr-xr-x.  1 root root     35048 Jul 21  2020  ipcrm*
-rwxr-xr-x.  1 root root     67816 Jul 21  2020  ipcs*
-rwxr-xr-x.  1 root root     14536 Dec  7  2019  ischroot*
-rwxr-xr-x.  1 root root     55672 Sep  5  2019  join*
-rwxr-xr-x.  1 root root     30952 May 28 17:27  kill*
-rwxr-xr-x.  1 root root     47336 Jul 21  2020  last*
lrwxrwxrwx.  1 root root         4 Jul 21  2020  lastb -> last*
-rwxr-xr-x.  1 root root     32416 May 28  2020  lastlog*
-rwxr-xr-x.  1 root root      5427 Dec 16  2020  ldd*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  link*
lrwxrwxrwx.  1 root root         7 Jul 21  2020  linux32 -> setarch*
lrwxrwxrwx.  1 root root         7 Jul 21  2020  linux64 -> setarch*
-rwxr-xr-x.  1 root root     76160 Sep  5  2019  ln*
-rwxr-xr-x.  1 root root     58944 Dec 16  2020  locale*
-rwxr-xr-x.  1 root root     14496 Jan 27  2021  locale-check*
-rwxr-xr-x.  1 root root    334808 Dec 16  2020  localedef*
-rwxr-xr-x.  1 root root     52040 Jul 21  2020  logger*
-rwxr-xr-x.  1 root root     57104 May 28  2020  login*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  logname*
-rwxr-xr-x.  1 root root    142144 Sep  5  2019  ls*
-rwxr-xr-x.  1 root root     14656 Feb 14  2020  lsattr*
-rwxr-xr-x.  1 root root    133352 Jul 21  2020  lsblk*
-rwxr-xr-x.  1 root root    100584 Jul 21  2020  lscpu*
-rwxr-xr-x.  1 root root     96488 Jul 21  2020  lsipc*
-rwxr-xr-x.  1 root root     39480 Jul 21  2020  lslocks*
-rwxr-xr-x.  1 root root     67816 Jul 21  2020  lslogins*
-rwxr-xr-x.  1 root root     67816 Jul 21  2020  lsmem*
-rwxr-xr-x.  1 root root     51440 Jul 21  2020  lsns*
-rwxr-xr-x.  1 root root       320 Jul 23 17:38  man*
-rwxr-xr-x.  1 root root    162552 Feb 16  2020  mawk*
-rwxr-xr-x.  1 root root     35120 Jul 21  2020  mcookie*
-rwxr-xr-x.  1 root root     47480 Sep  5  2019  md5sum*
lrwxrwxrwx.  1 root root         6 Sep  5  2019  md5sum.textutils -> md5sum*
-rwxr-xr-x.  1 root root     14568 Jul 21  2020  mesg*
-rwxr-xr-x.  1 root root     88408 Sep  5  2019  mkdir*
-rwxr-xr-x.  1 root root     67928 Sep  5  2019  mkfifo*
-rwxr-xr-x.  1 root root     72024 Sep  5  2019  mknod*
-rwxr-xr-x.  1 root root     47448 Sep  5  2019  mktemp*
-rwxr-xr-x.  1 root root     43160 Jul 21  2020  more*
-rwsr-xr-x.  1 root root     55528 Jul 21  2020  mount*
-rwxr-xr-x.  1 root root     14568 Jul 21  2020  mountpoint*
-rwxr-xr-x.  1 root root    149888 Sep  5  2019  mv*
-rwxr-xr-x.  1 root root     35048 Jul 21  2020  namei*
lrwxrwxrwx.  1 root root        22 Jul 23 17:35  nawk -> /etc/alternatives/nawk*
-rwsr-xr-x.  1 root root     44784 May 28  2020  newgrp*
-rwxr-xr-x.  1 root root     43352 Sep  5  2019  nice*
lrwxrwxrwx.  1 root root         8 Nov  7  2019  nisdomainname -> hostname*
-rwxr-xr-x.  1 root root     43448 Sep  5  2019  nl*
-rwxr-xr-x.  1 root root     43352 Sep  5  2019  nohup*
-rwxr-xr-x.  1 root root     43352 Sep  5  2019  nproc*
-rwxr-xr-x.  1 root root     35256 Jul 21  2020  nsenter*
-rwxr-xr-x.  1 root root     67992 Sep  5  2019  numfmt*
-rwxr-xr-x.  1 root root     72056 Sep  5  2019  od*
lrwxrwxrwx.  1 root root        23 Jul 23 17:35  pager -> /etc/alternatives/pager*
-rwxr-xr-x.  1 root root    121072 Jul 21  2020  partx*
-rwsr-xr-x.  1 root root     68208 May 28  2020  passwd*
-rwxr-xr-x.  1 root root     43384 Sep  5  2019  paste*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  pathchk*
-rwxr-xr-x.  2 root root   3478464 Oct 19  2020  perl*
-rwxr-xr-x.  2 root root   3478464 Oct 19  2020  perl5.30.0*
-rwxr-xr-x.  1 root root     30968 May 28 17:27  pgrep*
lrwxrwxrwx.  1 root root        14 Feb 13  2020  pidof -> /sbin/killall5*
-rwxr-xr-x.  1 root root     43384 Sep  5  2019  pinky*
lrwxrwxrwx.  1 root root         5 May 28 17:27  pkill -> pgrep*
-rwxr-xr-x.  1 root root     22904 Dec 16  2020  pldd*
-rwxr-xr-x.  1 root root     35064 May 28 17:27  pmap*
-rwxr-xr-x.  1 root root     76216 Sep  5  2019  pr*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  printenv*
-rwxr-xr-x.  1 root root     59736 Sep  5  2019  printf*
-rwxr-xr-x.  1 root root     39672 Jul 21  2020  prlimit*
-rwxr-xr-x.  1 root root    137688 May 28 17:27  ps*
-rwxr-xr-x.  1 root root     80280 Sep  5  2019  ptx*
-rwxr-xr-x.  1 root root     43352 Sep  5  2019  pwd*
-rwxr-xr-x.  1 root root     14568 May 28 17:27  pwdx*
lrwxrwxrwx.  1 root root         4 Jun 18  2020  rbash -> bash*
-rwxr-xr-x.  1 root root     51544 Sep  5  2019  readlink*
-rwxr-xr-x.  1 root root     51576 Sep  5  2019  realpath*
-rwxr-xr-x.  1 root root     22760 Jul 21  2020  rename.ul*
-rwxr-xr-x.  1 root root     14568 Jul 21  2020  renice*
lrwxrwxrwx.  1 root root         4 Feb 26  2020  reset -> tset*
-rwxr-xr-x.  1 root root     63720 Jul 21  2020  resizepart*
-rwxr-xr-x.  1 root root     14568 Jul 21  2020  rev*
-rwxr-xr-x.  1 root root        30 Jan 16  2020  rgrep*
-rwxr-xr-x.  1 root root     72056 Sep  5  2019  rm*
-rwxr-xr-x.  1 root root     47448 Sep  5  2019  rmdir*
-rwxr-xr-x.  1 root root     27144 Dec  7  2019  run-parts*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  runcon*
-rwxr-xr-x.  1 root root     10481 Dec  7  2019  savelog*
-rwxr-xr-x.  1 root root     55528 Jul 21  2020  script*
-rwxr-xr-x.  1 root root     30952 Jul 21  2020  scriptreplay*
-rwxr-xr-x.  1 root root     51296 Apr  8  2019  sdiff*
-rwxr-xr-x.  1 root root    121288 Dec 22  2018  sed*
-rwxr-xr-x.  1 root root      2442 Nov 17  2019  select-editor*
-rwxr-xr-x.  1 root root      1230 Nov 17  2019  sensible-browser*
-rwxr-xr-x.  1 root root      1169 Nov 17  2019  sensible-editor*
-rwxr-xr-x.  1 root root       452 Nov 17  2019  sensible-pager*
-rwxr-xr-x.  1 root root     51544 Sep  5  2019  seq*
-rwxr-xr-x.  1 root root     27136 Jul 21  2020  setarch*
-rwxr-xr-x.  1 root root     47344 Jul 21  2020  setpriv*
-rwxr-xr-x.  1 root root     14568 Jul 21  2020  setsid*
-rwxr-xr-x.  1 root root     47336 Jul 21  2020  setterm*
lrwxrwxrwx.  1 root root         6 May 28  2020  sg -> newgrp*
lrwxrwxrwx.  1 root root         4 Jul 18  2019  sh -> dash*
-rwxr-xr-x.  1 root root     51576 Sep  5  2019  sha1sum*
-rwxr-xr-x.  1 root root     59768 Sep  5  2019  sha224sum*
-rwxr-xr-x.  1 root root     59768 Sep  5  2019  sha256sum*
-rwxr-xr-x.  1 root root     67960 Sep  5  2019  sha384sum*
-rwxr-xr-x.  1 root root     67960 Sep  5  2019  sha512sum*
-rwxr-xr-x.  1 root root     63864 Sep  5  2019  shred*
-rwxr-xr-x.  1 root root     59736 Sep  5  2019  shuf*
-rwxr-xr-x.  1 root root     30952 May 28 17:27  skill*
-rwxr-xr-x.  1 root root     22768 May 28 17:27  slabtop*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  sleep*
lrwxrwxrwx.  1 root root         5 May 28 17:27  snice -> skill*
-rwxr-xr-x.  1 root root    117376 Sep  5  2019  sort*
-rwxr-xr-x.  1 root root     60184 Sep  5  2019  split*
-rwxr-xr-x.  1 root root     88440 Sep  5  2019  stat*
-rwxr-xr-x.  1 root root     51544 Sep  5  2019  stdbuf*
-rwxr-xr-x.  1 root root     84344 Sep  5  2019  stty*
-rwsr-xr-x.  1 root root     67816 Jul 21  2020  su*
-rwxr-xr-x.  1 root root     47456 Sep  5  2019  sum*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  sync*
-rwxr-xr-x.  1 root root     18744 Feb 26  2020  tabs*
-rwxr-xr-x.  1 root root     43352 Sep  5  2019  tac*
-rwxr-xr-x.  1 root root     72088 Sep  5  2019  tail*
-rwxr-xr-x.  1 root root    448112 Dec 16  2020  tar*
-rwxr-xr-x.  1 root root     35048 Jul 21  2020  taskset*
-rwxr-xr-x.  1 root root     43384 Sep  5  2019  tee*
-rwxr-xr-x.  1 root root     14360 Dec  7  2019  tempfile*
-rwxr-xr-x.  1 root root     55640 Sep  5  2019  test*
-rwxr-xr-x.  1 root root     92584 Feb 26  2020  tic*
-rwxr-xr-x.  1 root root     43800 Sep  5  2019  timeout*
-rwxr-xr-x.  1 root root     22776 May 28 17:27  tload*
-rwxr-xr-x.  1 root root     22840 Feb 26  2020  toe*
-rwxr-xr-x.  1 root root    129072 May 28 17:27  top*
-rwxr-xr-x.  1 root root    100728 Sep  5  2019  touch*
-rwxr-xr-x.  1 root root     26968 Feb 26  2020  tput*
-rwxr-xr-x.  1 root root     51544 Sep  5  2019  tr*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  true*
-rwxr-xr-x.  1 root root     43352 Sep  5  2019  truncate*
-rwxr-xr-x.  1 root root     31040 Feb 26  2020  tset*
-rwxr-xr-x.  1 root root     43352 Sep  5  2019  tsort*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  tty*
-rwxr-xr-x.  1 root root     15378 Dec 16  2020  tzselect*
-rwsr-xr-x.  1 root root     39144 Jul 21  2020  umount*
-rwxr-xr-x.  1 root root     39288 Sep  5  2019  uname*
-rwxr-xr-x.  2 root root      2346 Dec 13  2019  uncompress*
-rwxr-xr-x.  1 root root     43384 Sep  5  2019  unexpand*
-rwxr-xr-x.  1 root root     51576 Sep  5  2019  uniq*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  unlink*
-rwxr-xr-x.  1 root root     43448 Jul 21  2020  unshare*
-rwxr-xr-x.  1 root root     55712 Mar 23  2020  update-alternatives*
-rwxr-xr-x.  1 root root     14568 May 28 17:27  uptime*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  users*
-rwxr-xr-x.  1 root root     30952 Jul 21  2020  utmpdump*
-rwxr-xr-x.  1 root root    142144 Sep  5  2019  vdir*
-rwxr-xr-x.  1 root root     39168 May 28 17:27  vmstat*
lrwxrwxrwx.  1 root root        19 Jul 23 17:35  w -> /etc/alternatives/w*
-rwxr-xr-x.  1 root root     22760 May 28 17:27  w.procps*
-rwxr-sr-x.  1 root tty      35048 Jul 21  2020  wall*
-rwxr-xr-x.  1 root root     27208 May 28 17:27  watch*
-rwxr-xr-x.  1 root root     47456 Sep  5  2019  wc*
-rwxr-xr-x.  1 root root     35048 Jul 21  2020  wdctl*
-rwxr-xr-x.  1 root root     35496 Jul 21  2020  whereis*
-rwxr-xr-x.  1 root root       946 Dec  7  2019  which*
-rwxr-xr-x.  1 root root     59768 Sep  5  2019  who*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  whoami*
lrwxrwxrwx.  1 root root         7 Jul 21  2020  x86_64 -> setarch*
-rwxr-xr-x.  1 root root     76152 Feb 18  2020  xargs*
-rwxr-xr-x.  1 root root     39256 Sep  5  2019  yes*
lrwxrwxrwx.  1 root root         8 Nov  7  2019  ypdomainname -> hostname*
-rwxr-xr-x.  1 root root      1984 Dec 13  2019  zcat*
-rwxr-xr-x.  1 root root      1678 Dec 13  2019  zcmp*
-rwxr-xr-x.  1 root root      5880 Dec 13  2019  zdiff*
-rwxr-xr-x.  1 root root     26840 Dec 16  2020  zdump*
-rwxr-xr-x.  1 root root        29 Dec 13  2019  zegrep*
-rwxr-xr-x.  1 root root        29 Dec 13  2019  zfgrep*
-rwxr-xr-x.  1 root root      2081 Dec 13  2019  zforce*
-rwxr-xr-x.  1 root root      7585 Dec 13  2019  zgrep*
-rwxr-xr-x.  1 root root      2206 Dec 13  2019  zless*
-rwxr-xr-x.  1 root root      1842 Dec 13  2019  zmore*
-rwxr-xr-x.  1 root root      4553 Dec 13  2019  znew*
```

