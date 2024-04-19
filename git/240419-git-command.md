# Shell

## Shell이란

운영체제의 커널과 사용자를 연결해주는 소프트웨어

- sh(Bourne Shell): AT&T Bell 연구소의  Steve Bourne이 작성한 UNIX 쉘
- csh: 버클리의 Bill Joy가 작성한 UNIX 쉘
- bash(Bourne Again Shell): Brian Fox가 작성한 UNIX 쉘
    다양한 운영체제에서 기본쉘로 채택
- zsh: Paul Falstad가 작성한 UNIX 쉘

## Shell Command

$ ls
- 파일, 디렉토리 목록 출력/ list
- ls -a, ls -l, ls -la .....

$ cd {PATH}
- 해당 경로, 디렉토리로 이동/ change directory
- cd {상대경로}, cd {절대경로}

$ mkdir {directory name}
- 현재 위치한 디렉토리에 디렉토리 생성/ make directory
- mkdir {디렉토리 명}, mkdir {경로/디렉토리 명}
- 경로를 지정해 해당 위치에 디렉토리 생성 가능

$ pwd
- 현재 위치 출력/ print working directory

$ touch {file name}
- 해당 이름의 파일 생성
- 이미 파일이 존재할 시 해당 파일의 최종 수정시간 갱신
- 추가적인 작업은 없음

$ mv {file name} {PATH}
- 해당 이름의 파일을 해당 경로로 이동 / move
- 같은 디렉토리에 다른이름으로 옴길 시 이름 변경으로 사용 가능

$ cp {original file} {copied file}
- original file을 copied file의 이름으로 복사 / copy

$ rm {file name}
- 해당 파일 삭제 / remove
- rm -rf {directory name} / -rf옵션으로 디렉토리 삭제가능

$ cat {file name}
- 해당 파일 내용 출력
