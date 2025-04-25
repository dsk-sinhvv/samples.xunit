# Ticket
- [Mã số ticket trên Backlog](URL của Backlog)
 
## Những việc đã làm
- Đã đối ứng những gì trong pull request này?
- Nếu có phát sinh đối ứng thêm ngoài nội dung mô tả trong ticket, hãy ghi vào đây.
 
## Tại sao cần làm
- Những điểm bổ sung không thể diễn đạt rõ trong Backlog (nếu phần giải thích trong Backlog đã đầy đủ thì có thể bỏ qua mục này)
- Nếu có giải thích lý do tại sao đã đối ứng pull request này đối với ticket, reviewer sẽ dễ hiểu hơn.
 
## Những điểm cần được xem kỹ
Ví dụ như dưới đây:
```
Đã thiết lập giới hạn nhập ký tự 3 byte và 4 byte.
Đã kiểm tra các ký tự đó bằng xUnit và xác nhận hoạt động đúng như dự kiến,
nhưng vì là kiểm thử hộp đen (blackbox) nên không chắc chắn rằng đã cover được hết.
```
 
# Xác nhận hoạt động
- Đã kiểm tra hoạt động như thế nào và ở môi trường nào
 
# Self check
- [ ] Đã chạy xUnit trên máy local
- [ ] Không phát sinh lỗi cú pháp (syntax error)
- [ ] Check xem có thay đổi DB hay không, nếu có thì cũng đã sửa file SQL trong thư mục SQL
- [ ] Đã xác nhận nhánh sẽ merge vào
- [ ] Không để lại đoạn code không cần thiết (log dùng để debug, code bị comment, v.v.)
- [ ] Đã xem lại các phần có thể refactor
- [ ] Không bao gồm file không cần thiết ngoài nội dung ghi trong ticket
- [ ] Đã lấy (fetch) nội dung từ develop về và đã giải quyết conflict
- [ ] Đã ghi rõ "Những việc đã làm", "Tại sao cần làm", và "Xác nhận hoạt động" trong phần mô tả PR
- [ ] Đã xác nhận thay đổi không ảnh hưởng đến các chức năng khác
 
## Mục kiểm tra của reviewer
- [ ] Không phát sinh lỗi trong CI
- [ ] Nội dung self check không có vấn đề
- [ ] Nhánh merge không bị sai
- [ ] Nội dung thay đổi trong source code không sai lệch với nội dung mô tả trong ticket và PR
- [ ] Không bao gồm thay đổi ngoài phạm vi
- [ ] Phạm vi ảnh hưởng không có vấn đề
- [ ] Đã trao đổi với developer về các điểm đáng lo ngại trong quá trình review