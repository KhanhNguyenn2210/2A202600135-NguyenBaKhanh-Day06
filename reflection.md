# Individual reflection — Nguyễn Bá Khánh (2A202600135)

## 1. Role
Nạp dữ liệu cho Agent từ các chính sách của xanh SM

## 2. Đóng góp cụ thể
- Thiết kế file ingest.py
- Load dữ liệu từ các file dữ liệu do member up - document_loader.py 


## 3. SPEC mạnh/yếu
- Mạnh nhất: failure modes — nhóm nghĩ ra được case " AI trả lời lan man không đúng trọng tâm"
Ví dụ : đưa ra điều khoản chính sách cho user đọc
=> Tóm tắt lại và đưa ra gợi ý nếu không có xin lỗi và " không có trong tài liệu "

- Yếu nhất: ROI — 3 kịch bản thực ra chỉ khác là scale số lượng user 

  + nên tách thành thành số đoạn chat (trường hợp ) được xử lý trong ngày trong tháng trong tháng và lưu dữ liệu lại 

## 4. Đóng góp khác
- Tìm thêm tài liệu và gửi zalo cho Lực, Thư, Quỳnh tổng hợp lại 


## 5. Điều học được
- Trước hackathon chưa biết cách làm workflow như nào cho một dự án thực tế
- Chưa biết brainstorm với AI để viết code
- Chưa biết cách làm việc với github với team 

## 6. Nếu làm lại
- Sẽ brainstorm với AI về workflow, viết SPEC sớm.
- Sẽ đưa ra demo với MVP trước, không liệt kê ra quá nhiều phương án lan man như tính tiền nếu có thưởng hay giờ cao điểm 
- Nếu test sớm từ tối D5 thì sẽ tìm ra insight và đưa ra giải pháp cho team từ D6


## 7. AI giúp gì / AI sai gì
- **Giúp:** dùng Claude để brainstorm, viết code để xử lý upload dữ liệu 

  tìm ra lỗi sai trong workflow khi hợp code với team 
- **Sai/mislead:** Claude gợi ý thêm feature "đặt lịch khám" vào chatbot —
  nghe hay nhưng scope quá lớn cho hackathon. Suýt bị scope creep nếu không dừng lại.
  Bài học: AI brainstorm tốt nhưng không biết giới hạn scope.

  Claude gợi ý chọn thêm API của google map để lấy ra dữ liệu trạm sạc quá khó để giải quyết sớm nên nhóm đã gác lại tool này và đổi qua tool chính là tổng hợp chính sách 