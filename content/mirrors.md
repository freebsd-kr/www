---
title: "ftp.kr.freebsd.org 미러 사이트 정보"
---

ftp.kr.freebsd.org 는 FreeBSD 의 한국 공식 미러 사이트일 뿐 아니라 몇몇 오픈 소스를 미러링하고 있습니다.

# 접속 정보

* HTTPS - https://ftp.kr.freebsd.org/pub
  * 웹 브라우저나 http 클라이언트로 접근하세요.
* HTTP - http://ftp.kr.freebsd.org/pub
  * 웹 브라우저나 http 클라이언트로 접근하세요.
* FTP - ftp://ftp.kr.freebsd.org
  * ftp 클라이언트나 지원 가능한 웹 브라우저로 접근하세요.
* rsync - rsync://ftp.kr.freebsd.org
  * rsync 사용시에는 `rsync ftp.kr.freebsd.org::` 을 입력하면 다운로드 가능 목록을 볼 수 있습니다.

# 미러링 목록

정기적으로 업데이트되는 컨텐츠입니다. 공식의 경우 마스터 사이트에도 등록되어 있습니다.

{{<table "table table-striped table-bordered">}}
| 프로그램 | 미러 경로 | 마스터 사이트 | 갱신주기 | 공식 여부 | 비고 |
| --- | --- | --- | --- | --- | --- |
| FreeBSD | https://ftp.kr.freebsd.org/pub/FreeBSD | ftp://ftp-master.freebsd.org | 매일 | [공식](https://www.freebsd.org/doc/handbook/mirrors-ftp.html) ||
|CPAN| https://ftp.kr.freebsd.org/pub/CPAN | https://www.staff.science.uu.nl/~penni101/iim/ iim 사용|매일|[비공식](http://www.cpan.org/SITES.html)||
|ruby| https://ftp.kr.freebsd.org/pub/ruby|ftp://ftp.ruby-lang.org|매일|[공식](https://www.ruby-lang.org/en/downloads/mirrors/)||
|vim|https://ftp.kr.freebsd.org/pub/vim|ftp://ftp.home.vim.org/pub/vim|매일|[공식](https://www.vim.org/mirrors.php)|ftp.kr.vim.org = ftp.kr.freebsd.org 입니다|
|[안녕리눅스](http://annyung.oops.org/)|https://ftp.kr.freebsd.org/pub/AnNyung|http://mirror.oops.org/|매일|[공식](https://annyung.oops.org/?m=data&p=download)||
|DragonFlyBSD|https://ftp.kr.freebsd.org/pub/dragonflybsd|rsync://mirror-master.dragonflybsd.org|매일|[공식](https://www.dragonflybsd.org/mirrors/)||
|cygwin|https://ftp.kr.freebsd.org/pub/cygwin.com|rsync://cygwin.com|매일|[공식](http://cygwin.com/mirrors.html)||
|OpenVZ|https://ftp.kr.freebsd.org/pub/openvz|rsync://download.openvz.org/openvz-download|매일|[공식](​https://mirrors.openvz.org/)||
|x.org|https://ftp.kr.freebsd.org/pub/xorg|ftp://ftp.freedesktop.org|매일|[비공식](https://www.x.org/wiki/Releases/Download/)||
|~~postgresql~~|https://ftp.kr.freebsd.org/pub/postgresql|rsync://rsync.postgresql.org/pgsql-ftp|매일|비공식|중지(2025/5)|
|gimp|https://ftp.kr.freebsd.org/pub/gimp|rsync://master.gnome.org/gimp|매일|공식|
|~~openoffice~~|ftp://ftp.kr.freebsd.org/pub/openoffice|rsync://ftp.ussg.iu.edu/openoffice|매일|[비공식](http://download.services.openoffice.org/mirrors/all.html)|중지 (2019/2)|
|~~mozilla~~|ftp://ftp.kr.freebsd.org/pub/ftp.mozilla.org|http://ftp.mozilla.org|매일|비공식|중지 (2019/2)|
{{</table>}}

# 마스터 서버

ftp.kr.freebsd.org 가 마스터인 경우입니다.
* FreeBSD-kr: https://ftp.kr.freebsd.org/pub/FreeBSD-kr

# 복사본

업데이트되지 않지만 유지하고 있는 경우입니다.

* i18n-flp - https://ftp.kr.freebsd.org/pub/FreeBSD-jp/I18N-flp (ftp://daemon.jp.freebsd.org/pub/FreeBSD-jp/I18N-flp)
* PAO - https://ftp.kr.freebsd.org/pub/FreeBSD-jp/PAO (ftp://daemon.jp.freebsd.org/pub/FreeBSD-jp/PAO)
* jazz.snu.ac.kr - https://ftp.kr.freebsd.org/pub/jazz.snu.ac.kr
* kldp.net - https://ftp.kr.freebsd.org/pub/kldp.net
