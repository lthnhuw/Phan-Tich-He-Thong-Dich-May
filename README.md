# Phân Tích Hệ Thống Dịch Máy (Machine Translation System Analysis)  

## 1. Tổng Quan Dự Án  
- <b> Mục tiêu:</b> Phân tích và cải thiện chất lượng dịch máy Anh–Việt, đồng thời đánh giá các mô hình hiện có để đề xuất phương pháp hiệu quả nhất.
- <b> Vấn đề:</b> Các mô hình dịch cơ bản thường tạo ra bản dịch thiếu chính xác hoặc không tự nhiên, làm giảm tính ứng dụng trong thực tế.
- <b> Các bên liên quan: </b> Nhóm nghiên cứu, quản lý sản phẩm và người dùng cuối phụ thuộc vào hệ thống dịch.

## 2. Nhu Cầu và Mục Tiêu Kinh Doanh  
- Cung cấp bản dịch chính xác và tự nhiên nhằm nâng cao trải nghiệm người dùng.
- Xác định các phương pháp hiệu quả (ví dụ: hiệu chỉnh chính tả, dịch ngược) để nâng cao chất lượng dịch.
- Hỗ trợ quá trình ra quyết định trong việc lựa chọn mô hình dịch tốt nhất để triển khai.

## 3. Phân Tích Yêu Cầu  
- Yêu cầu chức năng:
  - Thu thập và tiền xử lý dữ liệu song ngữ.
  - Đánh giá chất lượng bản dịch bằng các chỉ số tiêu chuẩn.
  - So sánh giữa mô hình cơ bản và mô hình đã cải tiến.
- Yêu cầu phi chức năng:
  - Đảm bảo khả năng mở rộng với các bộ dữ liệu lớn hơn.
  - Cung cấp quy trình đánh giá minh bạch và có thể tái tạo.

## 4. Kỹ Thuật Phân Tích Kinh Doanh  
- <b> Chuẩn bị dữ liệu:</b> Làm sạch và cấu trúc lại bộ dữ liệu song ngữ Anh–Việt.
- <b> Phân tích so sánh:</b> Đánh giá nhiều mô hình dịch khác nhau, bao gồm Transformer cơ bản, mô hình đa nguồn và các hệ thống NMT được cải tiến.
- <b> Chỉ số đánh giá:</b> Sử dụng điểm BLEU để đo lường chất lượng bản dịch.
- <b> Tài liệu hóa:</b> Tổng hợp kết quả, phân tích và khuyến nghị cho các bên liên quan.

## 5. Kết Quả Chính  
- Bộ dữ liệu song ngữ Anh–Việt đã được tiền xử lý.
- Báo cáo đánh giá so sánh các mô hình dịch.
- Tài liệu về các phương pháp cải thiện chất lượng (hiệu chỉnh chính tả, dịch ngược).
- Đề xuất lựa chọn mô hình và hướng cải thiện trong tương lai.

## 6. Đánh Giá và Cải Tiến  
- <b> Hạn chế:</b> Một số thuật ngữ chuyên ngành vẫn khó dịch; việc đánh giá chỉ dựa trên điểm BLEU còn hạn chế.
- <b> Đề xuất cải tiến: </b>
  - Kết hợp đánh giá thủ công để đo độ tự nhiên và độ đầy đủ của bản dịch.
  - Mở rộng dữ liệu với nội dung chuyên biệt theo lĩnh vực.
  - Kiểm thử thêm các chỉ số đánh giá khác ngoài BLEU (ví dụ: METEOR, COMET).
   
## 7. Kỹ Năng Ứng Dụng  
Phân tích yêu cầu, chuẩn bị dữ liệu, đánh giá mô hình so sánh, viết tài liệu nghiệp vụ, trình bày nghiên cứu và báo cáo cho các bên liên quan.   

## 8. Phản Hồi & Tự Đánh Giá  
Quá trình thực hiện dự án này giúp nâng cao hiểu biết về dịch máy, khả năng phân tích mô hình và kỹ năng truyền đạt kết quả kỹ thuật sang ngôn ngữ kinh doanh.
