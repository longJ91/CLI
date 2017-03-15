# CLI (Command Line Interface)

#Basic Command (Linux)

>ls.
-현재 디렉토리에 포함된 파일 목록

ls -alt
-Option
1. \-a
모든 파일 나열 (숨겨진 파일까지 . .. 등으로 표현)
2. \-l
파일을 Long format 으로 표현 (접근 권한, 하위 디렉토리 수, 파일 소유자, 파일 쇼유자 그룹, 바이트 단위 크기, 파일 마지막 수정 시간, 파일 이름)
3. \-t
마지막 수정된 순서대로 나열

pwd
-현재 디렉토리의 주소

cd
-Working 디렉토리 이동

cd .. 
-상위 디렉토리로 이동

touch
-txt 와 같은 파일 생성

mkdir
-디렉토리 생성

cp 복사할파일(여러개 가능) 복사위치
-파일 복사 (cp *)

mv 파일이름 이동위치
-파일 이동

rm 파일 or 디렉토리
-파일 or 디렉토리(rm -r) 삭제 

echo
-입력(stdin) 후 출력(stdout)

cat
- file내용 출력

>
-왼쪽에서 발생한 output을 오른쪽으로 리디렉트한다.

>>
-왼쪽에서 발생한 output을 오른쪽의 새로운 file or old file로 리디렉트한다.

|
-완료된 output을 다른 command 로 더 사용

sort

uniq
-중복 필터

grep 
-텍스트 문장을 검색

grep -i 
-대 소 문자 구별 없이 검색

grep -R 주소
-해당 주소안 파일에서 검색후 출력

grep -Rl 주소
-텍스트 내용 생략후 출력

sed 's/snow/rain' file
-snow를 rain 변환 후 출력

sed 's/snow/rain/g' file
-모든 snow를 rain으로 변경 (만약에 한 문장에 snow가 2번 나오면 둘다 rain 변경)
