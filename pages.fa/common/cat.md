# cat

> چاپ و ترکیب کردن فایل ها.
>  اطلاعات بیشتر: <https://www.gnu.org/software/coreutils/manual/html_node/cat-invocation.html>.

- چاپ محتویات فایل بر روی صفحه نمایش:

`cat {{file}}`

- ادغام چند فایل با هم و ایجاد فایل جدید:

`cat {{file1}} {{file2}} > {{target_file}}`

- ادغام چند فایل با هم و اضافه کردن آن به فایل مقصد:

`cat {{file1}} {{file2}} >> {{target_file}}`

- شمارش تعداد خط های فایل:

`cat -n {{file}}`

- نمایش محتویات فایل بدون فضای خالی (نا مناسب برای چاپ):

`cat -v -t -e {{file}}`
