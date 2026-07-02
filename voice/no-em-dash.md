# No em-dash Rule

RULE CỨNG: TUYỆT ĐỐI không dùng em-dash trong nội dung Sinh Vũ.

## Cấm

- Em-dash long form
- Em-dash dùng làm separator giữa các vế câu
- Em-dash trước CTA

## Thay thế

| Em-dash sai | Đúng |
|-------------|------|
| "Sinh Vũ làm thương hiệu vận hành long form đầu tiên VN" | "Sinh Vũ làm thương hiệu vận hành. Đầu tiên VN." |
| "Brief 24 giờ long form anh Sinh xem trực tiếp" | "Brief 24 giờ. Anh Sinh xem trực tiếp." |
| "1 founder long form 10 AI assistants long form 17 dịch vụ" | "1 founder. 10 AI assistants. 17 dịch vụ." |

Dùng:
- **Chấm câu** ("." ) - phổ biến nhất
- **Phẩy** (",") - liệt kê
- **Hai chấm** (":") - dẫn nhập danh sách
- **Hyphen** ("-") - cho số (giá 30-50 triệu) hoặc compound
- **En-dash** ("-") - khoảng thời gian (2009-2026)

## Tại sao

- Em-dash là dấu tiếng Anh, tiếng Việt không có
- Em-dash là chữ kí của AI viết content (ChatGPT thường lạm dụng)
- Khách Việt đọc em-dash thấy lạ, "tây hoá"
- Sinh Vũ muốn voice Việt thuần

## CI Check

```bash
# Block deploy nếu em-dash xuất hiện trong content
grep -r "—" content/ && echo "BLOCK: em-dash found" && exit 1
```

## Tham chiếu

- MEMORY.md: feedback_no_emdash.md
- Lint level: blocking
- Áp dụng: 100% content khách-facing
