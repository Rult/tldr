# chmod

> 파일이나 디렉토리의 연결 권한 변경.
> 더 많은 정보: <https://www.gnu.org/software/coreutils/manual/html_node/chmod-invocation.html>.

- 파일을 소유한 사용자[u]에게 실행[x] 권한 부여:

`chmod u+x {{파일명}}`

- 파일/디렉토리에 읽기[r] 와 쓰기[w] 사용자 권한 부여:

`chmod u+rw {{파일명_또는_디렉토리명}}`

- 그룹[g]에서 실행 권한 제거:

`chmod g-x {{파일명}}`

- 모든[a] 사용자에게 읽기 및 실행 권한 부여:

`chmod a+rx {{파일명}}`

- 다른[o] 사람(파일 소유자의 그룹이 아님)에게 그룹과 동일한 권한 부여:

`chmod o=g {{파일명}}`

- 그룹[g] 및 다른 사람[o]에 대한 쓰기[w]에 대한 권한을 재귀적으로 변경:

`chmod -R g+w,o+w {{디렉토리명}}`
