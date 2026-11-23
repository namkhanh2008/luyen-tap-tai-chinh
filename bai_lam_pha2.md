# BÀI LÀM PHA 2 (ĐỀ LUYỆN TẬP CHỦ ĐỀ TÀI CHÍNH CÁ NHÂN)

- **Họ tên:TẠ ĐÌNH NAM KHÁNH**
- **Lớp:CNTT3**
- **Link repository Pha2:https://github.com/namkhanh2008/luyen-tap-tai-chinh**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):CHATGPT**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đăng ký hội thảo ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "DT",
    "ngay_hoi_thao": "2026-12-20",
    "nguoi_lon": 2,
    "tre_em": 1,
    "hang_ve": "thuong",
    "ghi_chu": null
  },
  {
    "ma_goi": "CB",
    "ngay_hoi_thao": "2027-01-10",
    "nguoi_lon": 3,
    "tre_em": 0,
    "hang_ve": "thuong",
    "ghi_chu": "cần lối đi riêng cho người sử dụng xe lăn"
  },
  {
    "ma_goi": "VIP",
    "ngay_hoi_thao": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "hang_ve": "vip",
    "ghi_chu": "người mắt kém cần ngồi bàn đầu gần màn hình chiếu"
  }
]
```

**Link trò chuyện:**https://chatgpt.com/share/6b03f19c-cce0-83ec-abbf-1a6e8562b996

## 4.3. Báo giá vé hội thảo bằng Chain-of-Thought

**KET QUA AI**

```text
1. Tiền người lớn

4 × 1.500.000 = 6.000.000 đồng

2. Tiền trẻ em
- Trẻ 8 tuổi: 1.500.000 × 50% = 750.000 đồng.
- Trẻ 11 tuổi: 1.500.000 × 50% = 750.000 đồng.
- Trẻ 4 tuổi: Miễn phí = 0 đồng.
Tổng: 750.000 + 750.000 + 0 = 1.500.000 đồng

3. Tiền vé

6.000.000 + 1.500.000 = 7.500.000 đồng

4. Giảm giá nhóm

Nhóm có 4 người lớn, đủ điều kiện giảm 10%.

7.500.000 × 10% = 750.000 đồng.

Tiền vé sau giảm:

7.500.000 − 750.000 = 6.750.000 đồng

5. Phụ thu sổ tay

2 × 200.000 = 400.000 đồng

6. Tổng tiền

6.750.000 + 400.000 = 7.150.000 đồng
Kết quả
[RESULT: 7150000 đồng]

**Link trò chuyện:**https://chatgpt.com/share/6b03f1db-1438-83ec-bd29-28e4f016a0a4

### b) Kiểm tra kết quả AI

AI ĐÚNG

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_khu_vuc",
  "so_khach": 2,
  "so_phien_bi_anh_huong": 2,
  "tom_tat": "Hai khách bị xếp vào khu vực thiếu bàn viết trong 2 phiên học đầu, không đúng quyền lợi cam kết."
}
```

**Link trò chuyện:**https://chatgpt.com/share/6b03f231-751c-83ec-a51c-7829adc9c368

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
Tiêu chí	Điểm	Minh chứng	Đề xuất sửa
Đúng thông tin (50%)	2/5	“Vé gói Đầu Tư bên em giá chỉ 1.200.000đ/người”; “hoàn lại đủ 100% tiền vé” – chưa có thông tin chuẩn của ban tổ chức để xác minh giá và chính sách hoàn vé.	Kiểm tra bảng giá và chính sách huỷ vé chính thức trước khi tư vấn. Không tự khẳng định mức hoàn tiền.
Đầy đủ (30%)	1/3	“Anh/chị báo huỷ trước 4 ngày...” – chưa mời khách cung cấp ngày hội thảo và số lượng vé đăng ký.	Bổ sung: “Anh/chị dự định tham dự ngày nào và muốn đăng ký bao nhiêu vé ạ?”
Giọng điệu (20%)	0,5/2	“Dạ chào anh/chị nha!”; “lời khủng”; “cứ yên tâm chốt đơn đi ạ!” – cách diễn đạt suồng sã, hứa hẹn lợi nhuận quá mức và gây áp lực mua hàng.	Sử dụng ngôn ngữ chuyên nghiệp, trung lập. Thay “lời khủng” bằng “trang bị kiến thức và kỹ năng đầu tư chứng khoán”.
Tổng điểm	3,5/10	Chưa đáp ứng đầy đủ yêu cầu về độ chính xác, tính đầy đủ và tính chuyên nghiệp.	Cần chỉnh sửa trước khi gửi khách hàng.
```

**Link trò chuyện:**https://chatgpt.com/share/6b03f29a-0dcc-83ec-aa84-179bd9a6ff14
