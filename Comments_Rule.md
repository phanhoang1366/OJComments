Bản fork OnlineJudge này đã được [Luyện Code](https://luyencode.net) thêm Markdown để tiện sử dụng (tương tự DMOJ, nhưng _đẹp hơn_).

Nếu bạn là một người chuyên sử dụng [Discord](https://discord.com/), có thể bạn đã tự mình sử dụng Markdown mà không hề hay biết (và bạn có thể áp dụng vào nó nữa!). Nếu không, hướng dẫn sau đây sẽ lấy một vài ví dụ về một số chức năng sẵn có của Markdown. Bên trên là ví dụ, bên dưới là kết quả.

- [Quy tắc thảo luận](#quy-tắc-thảo-luận)
- [Cách chèn code](#cách-chèn-code)
- [Cách ẩn lời giải](#cách-ẩn-lời-giải)
- [Hiệu ứng chữ](#hiệu-ứng-chữ)
- [Chèn ảnh](#chèn-ảnh)
- [Trả lời bình luận](#trả-lời-bình-luận)
- [Tài liệu đầy đủ](#tài-liệu-đầy-đủ)

# Quy tắc thảo luận
- Không bao giờ spam (nó không hề ngầu tí nào cả).
- Các nội dung chia sẻ gợi ý, source cần được ẩn (xem hướng dẫn [Cách ẩn lời giải](#cách-ẩn-lời-giải)).
- Đừng lộ thông tin cá nhân của mình, nếu không muốn bị người lạ trên mạng làm phiền.

# Cách chèn code
Có 2 chế độ chèn code là inline (liền-dòng) và block.
## Chèn code inline (liền-dòng)
```
Tìm `x` biết `x + 2 = 5`
```
Tìm `x` biết `x + 2 = 5`

## Chèn block code

Đối với chèn block code, bạn để code vào trong cặp 3 dấu "\`\`\`" (là phím dưới phím `ESC` đó). Ví dụ:

<pre>
```cpp
#include <stdio.h>
int main() {
  printf("Lap Trinh Khong Kho!");
  return 0;
}
```
</pre>

Kết quả:
```cpp
#include <stdio.h>
int main() {
  printf("Lap Trinh Khong Kho!");
  return 0;
}
```
**Lưu ý:** Bạn có thể sử dụng nhãn sau để làm đẹp code theo ngôn ngữ nhé:

- `cpp`: Ngôn ngữ C/C++
- `java`: Ngôn ngữ Java
- `py`: Ngôn ngữ Python
- `go`: Ngôn ngữ Golang
- `pas`: Ngôn ngữ Pascal
- Mặc định nếu không điền sẽ là `txt` và không có màu mè gì hết.

# Cách ẩn lời giải
- Các bạn **không nên** đăng code đã được AC của mình vào mục bình luận này. Thay vì đăng lời giải, hãy đăng gợi ý cách làm.
- Nếu bạn đăng gợi ý, hãy ẩn nó đi để người khác chỉ thấy khi họ thực sự cần được giúp đỡ:

````
Đây là lời giải của mình đã AC. Nếu bạn đã cố gắng mà chưa làm được thì có thể tham khảo lời giải của mình.
<details><summary>Xem code AC</summary>
<p>

```c
// Cho code vào đây và xóa 2 dòng này
main(){puts("Hello, World!");}
```

</p>
</details>
````

Đây là lời giải của mình đã AC. Nếu bạn đã cố gắng mà chưa làm được thì có thể tham khảo lời giải của mình.
<details><summary>Xem code AC</summary>
<p>

```c
// Cho code vào đây và xóa 2 dòng này
main(){puts("Hello, World!");}
```

</p>
</details>

# Hiệu ứng chữ
## Chữ bôi đậm
```
**Dòng này được bôi đậm**
```

**Dòng này được bôi đậm**

## Chữ in nghiêng

```
_Dòng này được in nghiêng_
```
_Dòng này được in nghiêng_

# Chèn ảnh
Đầu tiên, hãy upload ảnh của bạn lên một host nào đó. Ví dụ như https://imgur.com/. Sau đó copy đường dẫn ảnh nên có kết thúc là `jpg`, `png`, ... và chèn vào như sau:

```
![thẻ alt của ảnh](đường dẫn ảnh)
```

**Ví dụ:**
```
![Just a fun gif](https://media.giphy.com/media/PiQejEf31116URju4V/giphy.gif)
```
![Just a fun gif](https://media.giphy.com/media/PiQejEf31116URju4V/giphy.gif)

# Trả lời bình luận
Bạn có thể nhắc (mention) người đó hoặc trích dẫn bình luận của người đó để trả lời.
## Trích dẫn

Ví dụ:

```
> Khi nào thì phép chia không thực hiện được?

Khi số chia bằng 0
```

Kết quả:

> Khi nào thì phép chia không thực hiện được?

Khi số chia bằng 0

## Nhắc tên
Copy username của người đó và thêm `@` vào trước username đó. (Khá giống Discord và Messenger đúng không?)

Ví dụ, username của một bạn nào đó là `phanhoang1366` thì ta có thể nhắc tên như sau:
```
@phanhoang1366 you were a vtuber
```
Tuy nhiên, bạn phải vào web [Github](https://github.com) hoặc xem trên trang mình đã comment thì mới có thể nhận thông báo mình được trả lời.

# Tài liệu đầy đủ
1. [Full hướng dẫn sử dụng Markdown](https://guides.github.com/features/mastering-markdown/)
2. [Hướng dẫn Markdown bằng tiếng Việt](https://code2gio.com/huong-dan/su-dung-markdown-toan-tap/)
3. [Markdown Editor](https://markdown-editor.github.io/)

