---
tags:
  - obsidian
---
# Đây là hướng dẫn sử dụng Obsidian cho người dùng không chuyên IT
## Các Khái niệm
### Vault
Là kho chứ (thư mục chứa các ghi chú), đơn giản là bạn có thể tạo nhiều thư mục chứa nhiều note tổng, mỗi **Vault** có các plugin, theme riêng.
### Theme
Là màu nền của note ví dụ ảnh dưới là dùng theme *Minimal* và chọn color là *Dracula*
![[image.png]]
### Plugin
Là các phần mở rộng (extension/plugin) để thêm tính năng vào Obsidian do các người dùng, lập trình viên tạo ra cho cộng đồng cài vào để hỗ trợ và nâng cao tính năng.
### Cấu trúc note
Vault chỉ là tạo 1 thư mục lớn (hay không gian chứa note) còn thư mục mới là nơi chứa note thật sự. Các note sẽ dùng cú pháp **Markdown**. 
### Markdown là gì.
Nếu bạn không biết cú pháp Markdown thì có thể cài plugin *Editing toolbar* khi cài xong nó sẽ có thanh công cụ giống như Word.
![[image-1.png]]
Còn cú pháp markdown thì đọc ở phần dưới.

## Những extension cần thiết
### Theme
- Minimal theme (Dracula)
### Plugin
Các plugin được dùng trong Vault này. Ưu tiên cài càng ít càng tốt.

| tên                    | mô tả                                                                              | điểm cần thiết (thang 7) |
| ---------------------- | ---------------------------------------------------------------------------------- | ------------------------ |
| excalidraw             | Vẽ các hình ảnh canvas đơn giản                                                    | 4                        |
| minimal theme settings | Hỗ trợ các settings khác cho [[#Theme\| minimal theme]]                            | 5                        |
| style settings         | Hỗ trợ custom css tự động hoặc tự định nghĩa mạnh mẽ                               | 5                        |
| diarian                | Hỗ trợ daily note mạnh mẽ hơn                                                      | 6                        |
| Advanced Table         | Hỗ trợ table mạnh mẽ hơn                                                           | 6                        |
| Iconize                | Hỗ trợ icon cho file, folder                                                       | 4                        |
| Omnisearch             | Hỗ trợ OCR                                                                         | 6                        |
| Text extractor         | hỗ trợ cho omnisearch có khả năng đọc text trong pdf                               | 6                        |
| Linter                 | Format note                                                                        | 6                        |
| Image Converter        | Hỗ trợ định dạng, caption cho ảnh                                                  | 6                        |
| Text Formater          | Format text nhanh, hỗ trợ pasting format                                           | 5                        |
| Callout manager        | Hỗ trợ callout cho dễ dùng                                                         | 5                        |
| Editing toolbar        | Cực cần thiết nếu bạn là người dùng không chuyên. nó hỗ trợ toolbar giống như word | 7                        |
| Codeblock Customizer   | Hỗ trợ codeblock                                                                   | 6                        |
## Cú pháp Markdown
### Heading 
Là các đề mục (heading) khi bạn gõ nó sẽ có độ lớn và màu khác với các phần văn bản thường (paragraph). Khi gõ xong và xuống dòng thì Obsidian sẽ tự biến nó thành format to, nhỏ, màu sắc tuỳ vào các theme bạn cài.
Các heading từ 1 đến 6 bạn sẽ gõ dấu `#` và dấu cách sau đó đến tiêu đề. 
- Ví dụ: `# đây là heading 1`
- Kết quả: 
![[image-2.png|120x64]]
- tương tự với heading 2->6
```md
## đây là heading 2
Đây là văn bản thường
### đây là heading 3

###### đây là heading 6
```
- Kết quả:
![[image-3.png]]


### Paragraph
Đơn giản là văn bản thường, không bắt đầu bằng dấu `#` hoặc dấu khác như dấu `-`, `>` thì nó là văn bản thường

### Danh sách
Có 2 loại danh sách  (list) là danh sách có thứ tự và danh sách không thứ tự (unordered list)
#### Có thứ tự ví dụ
```
1. đây là mục 1
2. đây là mục 2
```
- Kết quả:
1. đây là mục 1
2. đây là mục 2
#### Không có thứ tự
```md
- đây là item 1
- Đây là item 2
```
Kết quả nó sẽ biến thành các dấu chấm tròn
- đây là item 1
- Đây là item 2
### Callout
Là các khối ghi chú nổi, vi dụ

> [!NOTE] Đây là một callout
> Cách tạo bằng cách gõ `/insertcallout` và nhấn `enter`
/insertcal

> [!Error] Đây là callout khác
> Contents

Có thể dùng cái plugin là `Callout Manager để tạo cho dễ`

### Codeblock
Là các khối code lập trình, hiển thị cho đẹp. Tạo ra bằng cách gõ dấu  3 lần, và đóng lại 3 lần. Dấu này ở trên phím `Tab`, có tên gọi là blacktick
![[image-4.png]]
Ví dụ: đây là 1 đoạn code python. Tác dụng là có hiển thị màu cho code, và có nút bên phải góc trên để copy khi nhấn vào.
```python
# đây là comment
print('xin chao')
```
### Table
Tạo bảng bằng cách gõ `/table` -> chọn insert table bằng cách nhân enter.

![[image-5.png]]

| Tiêu đề 1 | Tiêu đề 2 |
| --------- | --------- |
| 1         | giá trị   |
### Dấu ngắt dòng
cú pháp: 3 dấu trừ (hay còn gọi là hyphen) `---`. sau khi xuống dòng mới nó sẽ hiện 1 đường ngang. nhớ là phải chừa ít nhất 1 dòng sau sau đó mới thêm 3 dấu - nha.

Tạm thời cơ bản nhiếu đó thôi.
## Kết quả
![[image-6.png]]