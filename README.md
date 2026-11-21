# data_analysis_e-comm
Dự án phân tích dữ liệu shoppe với mục tiêu tìm ra lý ro giao hàng kém hiệu quả so với quý trước

Bối cảnh:
- Dữ liệu là đơn hàng mô phỏng trên sàn Shopee, từ 01/01 đến 30/06/2026, snapshot ngày 01/07/2026. Bộ dữ liệu có 50.000 đơn của 12.000 khách, 150 seller và 3 hãng vận chuyển giao hàng giữa 6 thành phố. 
- Sang Q2, số đơn tăng 13% so với Q1 nhưng chất lượng giao hàng đi xuống rõ: tỷ lệ đơn giao trễ tăng từ 5,7% lên 15,1%, tỷ lệ hủy tăng từ 4,1% lên 5,3%.

Mục tiêu:
- Tăng trưởng: Đơn hàng và GMV thay đổi
thế nào theo tháng? Tăng trưởng đến từ số
đơn hay từ giá trị mỗi đơn?
- Seller rủi ro: Seller nào vừa hủy hoặc trễ
nhiều, vừa có đủ nhiều đơn để đáng lo?
-Nguyên nhân trễ: Đơn trễ là do seller xử lý
chậm hay do hãng vận chuyển giao chậm, và ở
seller, hãng, tuyến nào?
-Chất lượng hãng vận chuyển: Hãng nào kém
đi, kém ở tuyến nào, và từ khi nào?
-Ưu tiên hành động: Nếu chỉ xử lý được 10 seller và
3 tuyến giao hàng thì chọn ai, vì sao, và đo kết
quả sau khi sửa bằng chỉ số nào?
