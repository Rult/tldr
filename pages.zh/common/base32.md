# base32

> 将文件或标准输入编码到Base32或从Base32解码为标准输出。
> 更多信息： <https://www.gnu.org/software/coreutils/manual/html_node/base32-invocation.html>.

- 编码一个文件:

`base32 {{文件名}}`

- 解码一个文件:

`base32 --decode {{文件名}}`

- 从标准输入编码:

`{{某指令}} | base32`

- 将标准输入解码:

`{{某指令}} | base32 --decode`
