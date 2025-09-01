# 📊 Báo Cáo Cuối Kỳ - Tương Tác Dữ Liệu Trực Quan  

## 📝 Thông tin chung  
- **Đề tài**: Câu chuyện dữ liệu về ngành bán lẻ  
- **Môn học**: Tương Tác Dữ Liệu Trực Quan  
- **Trường**: Đại học Sư Phạm Kỹ Thuật TP. Hồ Chí Minh  
- **Khoa**: Công nghệ Thông tin  

---

## 📖 Mô tả dự án  
Báo cáo này tập trung phân tích dữ liệu bán lẻ từ tập dữ liệu **Superstore**, mô phỏng hoạt động kinh doanh của một công ty bán lẻ tại Hoa Kỳ.  

**Mục tiêu**:  
- Sử dụng các kỹ thuật trực quan hóa dữ liệu để khám phá hiệu suất kinh doanh.  
- Tìm hiểu xu hướng mua sắm và các yếu tố ảnh hưởng đến lợi nhuận.  
- Đưa ra đề xuất nhằm cải thiện chiến lược kinh doanh.  

---

## 📂 Nội dung chính  
- **Tóm tắt (Abstract)**: Giới thiệu tổng quan về dữ liệu và mục tiêu phân tích.  
- **Giới thiệu (Introduction)**: Xác định câu hỏi nghiên cứu về hiệu suất kinh doanh, hành vi khách hàng, và chiến lược tối ưu hóa.  
- **Dữ liệu (Data)**: Nguồn dữ liệu Superstore, tiền xử lý và lý do giữ nguyên các giá trị ngoại lai.  
- **Kể chuyện dữ liệu (Storytelling Data)**:  
  - **Mở đầu**: Thành tựu kinh doanh giai đoạn 2011–2014.  
  - **Đặt vấn đề**: Mâu thuẫn giữa doanh thu tăng trưởng và lợi nhuận thấp.  
  - **Nguyên nhân**: Phân tích đơn hàng lỗ, chiết khấu không hiệu quả, vận chuyển tốn kém, chiến lược khách hàng chưa rõ ràng.  
  - **Giải pháp**: Kiểm soát đơn hàng lỗ, phân tầng chiết khấu, tái cấu trúc danh mục sản phẩm, tùy chỉnh chiến lược theo khu vực địa lý.  
- **Kết luận**: Tóm tắt phát hiện, nhấn mạnh tầm quan trọng của tái cấu trúc chiến lược để tăng trưởng bền vững.  

---

## 📊 Dữ liệu sử dụng  
- **Nguồn dữ liệu**: Superstore Sales Dataset.  
- **Thông tin chính**: Đơn hàng, khách hàng, sản phẩm, doanh thu, chiết khấu, lợi nhuận.  
- **Tiền xử lý**:  
  - Xử lý giá trị null và duplicates.  
  - Chuyển đổi `Order Date`, `Ship Date` sang `DateTime`.  
  - Tạo cột `Year`, `Month`, `Day` để hỗ trợ trực quan hóa.  
  - Giữ nguyên các giá trị ngoại lai để phản ánh thực tế kinh doanh.  
  - Tạo cột viết tắt tiểu bang để vẽ bản đồ.  

---

## 🛠️ Công cụ và phương pháp  
- **Công cụ**: Python, Superset
- **Phương pháp phân tích**:  
  - Phân tích tương quan giữa chiết khấu và lợi nhuận.  
  - Phân cụm để tìm nhóm khách hàng/sản phẩm tiềm năng.  
  - Trực quan hóa dữ liệu qua nhiều loại biểu đồ.  

---

## ✅ Kết quả đạt được  
- Xác định các vấn đề chính gây ra sự chênh lệch giữa doanh thu và lợi nhuận.  
- Phát hiện các danh mục sản phẩm kém hiệu quả (Tables, Bookcases, Supplies).  
- Chỉ ra các khu vực địa lý gây lỗ (Texas, Central).  
- Đề xuất giải pháp: kiểm soát chiết khấu, tối ưu vận chuyển, phân tầng khách hàng.  

---

## 📌 Lưu ý  
- Báo cáo dựa trên dữ liệu Superstore, mang tính **giáo dục** và **thực hành**.  
- Không phản ánh chính xác toàn bộ tình hình kinh doanh thực tế.  
