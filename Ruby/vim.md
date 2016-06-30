#vim 사용법
    $vi : 빔 켜기

    vim 내부에서..
    i  [insert]
    :  [명령어 입력.]
    :w [파일이름 : 저장하기.]
    :q [빔 종료]
    HJKL [빔 이동]
    e [단어 맨 마지막 문자]
    w [단어 맨 첫번째 문자]
    b [바로 이전 단어의 첫번 째 문자로 커서 이동]
    $ [현재 위치한 행의 맨 마지막 문자로..]
    ^ [현재 위치한 행의 맨 처음으로..]
    gg[현재 파일 내용의 맨 첫번째 행으로..]
    G [현재 파일 내용의 맨 마지막으로..]
    x [삭제]
    dd [행 코드 전체삭제]
    x [현재 커서 문자 삭제]
    X [현재 커서 위치의 한 칸 앞의 문자를 삭제]
    dd [행 전체 삭제]
    dw [현재 커서 위치부터 현재 위치한 단어의 마지막 부분까지..]
    d$ [현재 커서 위치에서부터 현재 위치한 행의 맨 마지막 부분까]지
    y [복제]
    p [붙여넣기]
    V전체 선택 y복사 p붙여넣기
    yy 한 행 전체 붙여넣기.
    dw :delete words?
    u [undo]
    Ctrl + r [다x시 실행]
    Ctrl + f [아랫방]
    Ctrl + b [윗 방향]
    단어찾기 => :/W3
    :%s/[대상단어]/[바꿀단어]
    :vs . 스크린 나누기.
    :sp : 
    Ctrl + ww  화면 전환

#띄어쓰기 옵션
    :set nu
    :set nonu
    :set ts=2 (tab size)
    :set sw=2 (set shift width)
    :set ai (auto indent)
    :set paste (붙여넣기 특화)
    :colorscheme <색상 테마 이름>
    :set paste 계단 현상 제거.

#옵션 저장
    $vi ~/.vimrc


