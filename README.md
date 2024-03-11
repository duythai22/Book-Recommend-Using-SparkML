Tập dữ liệu "Book-Crossing: User Review Ratings" chứa thông tin về đánh giá từ người dùng về các cuốn sách trên trang web Book-Crossing. Tập dữ liệu bao gồm thông tin về cuốn sách, người đánh giá và điểm đánh giá. Đây là tập dữ liệu lý tưởng cho việc nghiên cứu về đánh giá sách và các hệ thống gợi ý sách.

Tập dữ liệu được thu thập từ trang web Book-Crossing và được chia sẻ trên Kaggle bởi người dùng ruchi798. Dữ liệu gốc bao gồm các tệp CSV chứa thông tin về sách (BX-Books.csv), người dùng (BX-Users.csv) và đánh giá (BX-Book-Ratings.csv). Và 1 tập là Summaryyy.parquet được tách ra từ tập Preprocessed_data.csv của link dataset.

Mô tả chi tiết các tập dữ liệu:

1. BX-Books.csv

- User-ID: Id của người đọc.
- ISBN: Mã của quyển sách.
- Book-Ratting: Điểm đánh giá của người đọc cho quyển sách.

2. BX-User.csv

- User-ID: Id của người đọc.
- Location: Địa chỉ người đọc.
- Age: Số tuổi của người đọc.

3. BX_Books.csv

- ISBN: Mã của quyển sách.
- Book-Title: Tên của quyển sách.
- Book-Author: Tác giả của quyển sách.
- Year-Of-Publication: Năm phát hành quyển sách.
- Publisher: Nhà xuất bản.
- Image-URL-S: link hình ảnh với size nhỏ.
- Image-URL-M: link hình ảnh với size vừa.
- Image-URL-L: link hình ảnh với size lớn.

4. Summaryyy.parquet

- ISBN: Mã của quyển sách.
- Summary: Mô tả tóm tắt nội dung quyển sách.
