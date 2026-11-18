## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "SVT",
    "ngay_su_kien": "2026-12-20",
    "nguoi_lon": 2,
    "tre_em": 1,
    "loai_ve": "thuong",
    "ghi_chu": null
  },
  {
    "ma_goi": "FZ",
    "ngay_su_kien": "2027-01-05",
    "nguoi_lon": 3,
    "tre_em": 0,
    "loai_ve": "thuong",
    "ghi_chu": "hỗ trợ xe lăn"
  },
  {
    "ma_goi": "VIP",
    "ngay_su_kien": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "loai_ve": "vip",
    "ghi_chu": "hỗ trợ tìm chỗ"
  }
]
```

**Link trò chuyện:**https://share.gemini.google/DwjecfDPUl4Z

## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**

```text
1. Tiền người lớnSố lượng người lớn: 5 ngườiGiá vé người lớn (SVT): 1.200.000 đồng/ngườiPhép tính: $5 \times 1.200.000 = 6.000.000$ đồng2. Tiền trẻ emTrẻ em từ 5 đến 11 tuổi tính 70% giá người lớn.Nhóm có 2 trẻ em trong độ tuổi này (8 tuổi và 10 tuổi); bé 3 tuổi dưới 5 tuổi được miễn phí (0 đồng).Phép tính: $2 \times (1.200.000 \times 70\%) = 2 \times 840.000 = 1.680.000$ đồng3. Tiền vé (Tổng tiền vé trước giảm giá)Phép tính: $\text{Tiền người lớn} + \text{Tiền trẻ em} = 6.000.000 + 1.680.000 = 7.680.000$ đồng4. Giảm giá nhómNhóm có 5 người lớn (đạt điều kiện từ 5 người lớn trở lên), được giảm 5% trên tổng tiền vé.Phép tính: $7.680.000 \times 5\% = 384.000$ đồngTiền vé sau giảm: $7.680.000 - 384.000 = 7.296.000$ đồng5. Phụ thuCó 1 người lớn chọn khu ghế ưu tiên với mức phụ thu 300.000 đồng/người (phụ thu không được giảm giá).Phép tính: $1 \times 300.000 = 300.000$ đồng6. Tổng tiềnTổng tiền = Tiền vé sau giảm + Phụ thuPhép tính: $7.296.000 + 300.000 = 7.596.000$ đồng[RESULT: 7.596.000 đồng]
```

**Link trò chuyện:**https://share.gemini.google/0qadMlQkZzYE

### b) Kiểm tra kết quả AI

Kết quả của Ai đã đưa ra là đúng.

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
[
  {
    "loai_su_co": "sai_khu_vuc",
    "so_khach": 2,
    "so_hiep_bi_anh_huong": 2,
    "tom_tat": "Khán giả mua vé gói SVT cho 2 người lớn bị xếp sai sang khu không mái trong 2 hiệp đầu, yêu cầu giải quyết đền bù theo chính sách."
  }
]
```

**Link trò chuyện:**https://share.gemini.google/AAuMlhbJmVRA
