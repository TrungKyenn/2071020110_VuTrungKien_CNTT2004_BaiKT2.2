# Báo cáo lỗi

Đã rà soát các trang HTML và CSS trong thư mục dự án. Các lỗi dưới đây nằm trong `2071020110_VuTrungKien_2004_lab5/index.html`.

| Mức độ | Dòng | Lỗi | Ảnh hưởng |
|---|---:|---|---|
| Cao | 68 | Trường email dùng `type="___"` và thuộc tính `___` thay vì `type="email"` và `required`. | Trình duyệt không kiểm tra định dạng email; người dùng có thể gửi form khi để trống email dù nhãn ghi bắt buộc. |
| Trung bình | 63 | Nhãn họ tên có `for="___"` nhưng ô nhập có `id="fullname"`. | Nhãn không được liên kết với ô nhập; bấm nhãn không đưa con trỏ vào ô và công nghệ hỗ trợ có thể không nhận đúng tên trường. |
| Trung bình | 73 | Giá trị `minlength="___"` và `maxlength="___"` không phải số hợp lệ. | Ràng buộc độ dài nội dung không hoạt động; người dùng không bị giới hạn từ 10 đến 500 ký tự như phần hướng dẫn. |
| Trung bình | 74 | `aria-describedby="___"` không trỏ đến phần tử trợ giúp `id="message-help"`. | Trình đọc màn hình không nhận được hướng dẫn độ dài cho trường nội dung. |
| Thấp | 77 | Nút có `type="___"` không phải giá trị hợp lệ cho thuộc tính `type`. | HTML không hợp lệ; hiện tại trình duyệt thường mặc định nút trong form thành nút gửi, nhưng hành vi dựa vào giá trị mặc định thay vì khai báo rõ `type="submit"`. |

**Ghi chú:** Các giá trị `___` có vẻ là chỗ trống chưa được điền trong bài thực hành. Chưa sửa mã nguồn; báo cáo này chỉ ghi lại các lỗi tìm thấy.