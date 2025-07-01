# New-Instruction

Java 프로젝트 처음 시작할 때 사용하는 Git 명령어 정리입니다:

```java
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello, bro!");

    /* 
    first project commit시
    - git init
    어떤 파일을 git에 올릴지 확인(. : all files)
    - git add .
    올릴 files check
    - git status
    history 생성
    - git commit -m "first commit"
    github와 연결고리 생성
    - git remote add origin https://github.com/사용자명/리포지토리명.git
    연결고리 확인
    - git remote -v
    github에 올리기(first push시 -u 사용. 이후 push, pull시 git push, git pull만 사용가능) 
    (git branch로 main인지 master인지 확인)
    - git push -u origin main

    원격 주소 변경하고 다시 등록(기존 주소가 잘못된 경우에만!!)
    - git remote remove origin
    - git remote add origin https://github.com/사용자명/폴더명.git
     */
  }
}
