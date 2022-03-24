Ubuntu Server 20.04 Apache2 Error 페이지 수정하기


/etc/apache2/sites-av* 이동후
conf파일 오픈후 수정

아래 코드 적절한곳에 코드 추가

ErrorDocument 404 /404.html

이후 404.html 및 img 파일 /var/www/html 루트에 업로드후

아파치 재시작하면 적용됨
