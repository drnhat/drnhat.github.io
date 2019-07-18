---
layout: post
title: Định dạng todo.txt
subtitle: Một định dạng quản lý thời gian
tags: [todo.txt]
---
Mình sử dụng phần mềm sắp xếp công việc thì cũng nhiều rồi. Từ thời còn dùng Blackberry thì đã tập dùng Task, rồi đọc đâu đó phương pháp GTD thế là mò cài chương trình NextAction! (vẫn còn cài trên máy 9900). Qua các máy điện thoại mới hơn thì cũng dùng thử qua Wunderlist, Any.do, Remember the milk… Dùng cho lắm vô rốt cuộc chẳng có chương trình mình theo nên hồn, chủ yếu do nhác quá.

Trong đống đó mình rất kết 1 cái, dù dùng chưa được trọn vẹn với nó nhưng theo nó cũng được từ lâu rồi. Đó là hồi mình tìm hiểu về Sublime Text có đọc về todo.txt từ cái trang web [này](http://plaintext-productivity.net). Hồi đó thấy hay dễ sợ, thế là cài cho Windows phần mềm todo.net, rồi đồng bộ trên điện thoại Windows Phone phần mềm sử dụng định dạng todo.txt luôn, sync tất cả qua Dropbox. Thời gian trôi qua lại nhác nhớm. Bây giờ trải qua thêm một số biến cố, sử dụng lại todo.txt thì thấy những task cũ của mình vẫn còn nguyên ở đó, đúng là định dạng Paintext ưu điểm tuyệt vời chỗ đó. Thôi thì cố gắng sử dụng nó đàng hoàng để công việc mình đỡ bị rối tinh rối mù, hay ít nhất là có làm việc đàng hoàng chút.

# Định dạng file todo.txt

![todo.txt](https://i.imgur.com/IGbdj5x.png)

## Cơ bản

Mỗi dòng là một nhiêm vụ:

`Viết về todo.txt`

Để phân loại công việc quan trọng thì thêm (A); (B)...

`(A) Viết về todo.txt`

Để phân loại theo Context thì thêm @context (Context có thể hiểu là nơi để làm công việc đó)

`(A) Viết về todo.txt @laptop`

Để phân loại dự án Project thì thêm +project (Nếu một công việc nhiều nhiệm vụ thì phân làm nhiều việc nhỏ trong một Project lớn)

`(A) Viết về todo.txt @laptop +gtd`

Ngày khởi tạo công việc viết ngay sau phân loại độ quan trọng công việc (định dạng yyyy-mm-dd)

`(A) 2019-06-04 Viết về todo.txt @laptop +gtd`

Khi hoàn thành nhiệm vụ thì thêm `x` trước nhiệm vụ đó, thời gian hoàn thành ngay trước thời gian tạo công việc.

`(A)2019-06-05 2019-06-04 Viết về todo.txt @laptop +gtd`

## Mở rộng

Hạn cuối cần hoàn thành công việc, thêm `due:yyyy-mm-dd`

`(A) 2019-06-04 Viết về todo.txt @laptop +gtd due:2019-06-04`

Thời gian công việc có thể bắt đầu được, thêm `t:yyyy-mm-dd`

`(A) 2019-06-04 Viết về todo.txt @laptop +gtd t:2019-06-04`

Trong trường hợp công việc có tính chất lặp lại, công việc cần phải có Due date/threshold, khi đó mỗi khi hoàn thành công việc thì phần mềm hỗ trợ sẽ tạo thêm một công việc tương tự có due date/threshold cách ngày hoàn thành 1 khoảng thời gian cài trước. Thêm `rec:\+?[0-9]+[dwmyb]`. (**d**ay, **w**eek, **m**onth, **y**ear, **b**usinedday)

`(A) 2019-06-04 Viết về todo.txt @laptop +gtd due:201-06-04 rec:1b`

# Các phần mềm
Vì là định dạng mở nên có kha khá phần mềm sử dụng định dạng này được, và hỗ trợ khá tốt. Có thể kể tới: 
- Trên Macbook hiện tại mình dùng [TodoTxtMac](https://mjdescy.github.io/TodoTxtMac/) (Free).
- Trên Android hiện tại mình đang đùng [SimpleTask](https://github.com/mpcjanssen/simpletask-android/blob/master/app/src/main/assets/index.en.md) (Free).
- Trên Windows trước đây mình dùng [Todotxt.net](https://github.com/benrhughes/todotxt.net) (Free)
- Trên iOS có SwiftDo.
Nhìn chung thì hai chương trình này đều có những phần mở rộng tương đương nhau. Đồng bộ hóa trên Dropbox rất tốt. Tuy nhiên sẽ có nhược điểm là bất lợi khi lên lịch cộng việc khi đang Offline mà ở [đây](http://rtalbert.org/back-to-todoist/) có nói (mình cũng từng bị). Nói chung biết bất lợi của nó mà tránh thôi.
# Kết luận
Nhìn chung mình hài lòng với định dạng và chương trình đang có, cũng có vài nhược điểm nhưng biết để mà khắc phục. Điều quan trọng là mình cần là người làm việc có khoa học hơn. Tuân thủ tốt hơn lịch công tác đề ra, tránh sao nhãng. Công cụ là 1 phần nhưng mà còn con người nữa.









