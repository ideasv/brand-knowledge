# "Anh / Chị" Customer Honorific Rule

Sinh Vũ xưng hô khách bằng "Anh / Chị" (tiếng Việt: vai vế).

## Pattern

- **Default lịch sự**: `Anh / Chị` (có khoảng trắng quanh slash, viết hoa A và C)
- **Khi biết giới tính nam**: `Anh`
- **Khi biết giới tính nữ**: `Chị`
- **Khi khách lớn tuổi rõ rệt (gen parent)**: `Cô` / `Chú`

## Sai vs Đúng

| Sai | Đúng |
|-----|------|
| "Bạn muốn làm gì?" | "Anh / Chị muốn làm gì?" |
| "anh chị" (viết thường) | "Anh / Chị" (viết hoa, có khoảng trắng) |
| "Bạn ơi" / "Em chào bạn" | "Sinh Vũ chào Anh / Chị" |
| "Quý khách" | "Anh / Chị" (gần gũi hơn) |

## Sinh Vũ xưng hô lại

- Trong content khách-facing: "Sinh Vũ" (third-person)
- Trong chat 1-1 với khách peer (cùng gen): "em" (peer)
- Trong chat 1-1 với khách parent gen (Cô/Chú): "cháu"

## Tại sao

- Khách Việt cảm thấy được tôn trọng với "Anh / Chị"
- "Bạn" quá suồng sã cho B2B
- "Quý khách" quá cứng cho startup, founder gen Z/millennial
- Có khoảng trắng quanh slash → dễ đọc, không bị parser lỗi

## Áp dụng

- Mọi page sinhvu.com
- Mọi email khách
- Mọi micro-copy
- Chat AI collector
- Form labels

## Tham chiếu

- Lint CI: regex `\banh\s*/\s*chị\b` (case sensitive) phải có khoảng trắng
- "bạn" / "quý khách" trong micro-copy → block deploy
