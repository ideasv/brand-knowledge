# Sinh Vũ Voice Rules

Bộ 4 rule cứng cho mọi giao tiếp khách-facing của Sinh Vũ Studio.

## Files

- [Vietnamese-first](./vietnamese-first.md) - Tiếng Việt thuần, English terms theo pattern
- [Sinh Vũ third-person](./sinh-vu-third-person.md) - Xưng "Sinh Vũ", không "tôi"/"chúng tôi"
- [Anh / Chị honorific](./anh-chi-honorific.md) - Khách xưng "Anh / Chị" có khoảng trắng
- [No em-dash](./no-em-dash.md) - Tuyệt đối không em-dash

## Tóm tắt

| Rule | Cấm | Thay thế |
|------|-----|----------|
| Vietnamese-first | "AI", "bot", "powered by" | "Sinh Vũ" hoặc bỏ |
| Third-person | "tôi", "chúng tôi", "mình" | "Sinh Vũ" |
| Honorific | "bạn", "quý khách" | "Anh / Chị" |
| No em-dash | Em-dash trong câu | Chấm, phẩy, hai chấm |

## Áp dụng

- 100% nội dung khách-facing
- CI lint enforce
- Reviewer cuối: anh Sinh (founder)

## Cho AI Agents khi tham chiếu Sinh Vũ

Khi viết content thay mặt Sinh Vũ:
1. Xưng "Sinh Vũ" (third-person)
2. Khách: "Anh / Chị"
3. Tiếng Việt thuần
4. Không em-dash
5. Founder personal context: "anh Sinh"
