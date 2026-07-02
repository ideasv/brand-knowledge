# 40 Sub-niche Research Packs · Sinh Vũ R009

Bộ 40 packs JSON từ R009 deep research (~500 nguồn) - knowledge dùng để cá nhân hoá brief theo sub-niche. Mỗi pack được áp 1 trong 3 patterns + 5 input types.

## Patterns

| Pattern | Tên | Áp cho | Ví dụ |
|---------|-----|--------|-------|
| A | Production goods | Sản phẩm vật lý có SKU | Mỹ phẩm, F&B, OCOP |
| B | Service + Digital | Dịch vụ + sản phẩm số | SaaS, edu, fintech |
| C | Document + Knowledge | Tri thức, tài liệu | Tư vấn, luật, kế toán |

## 5 Input Types

| Type | Tên VN | Áp cho |
|------|--------|--------|
| `single_select` | Chọn 1 | Quyết định mutually exclusive |
| `multi_select` | Chọn nhiều | Combinations |
| `text_field` | Trường tự nhập | Tên thương hiệu, mô tả riêng |
| `yes_no` | Có / Không | Boolean |
| `number` | Số | Ngân sách, timeline weeks |

## 5 Input Categories per Pack

Mỗi pack chuẩn hoá 5 input categories:
1. **brand_status** - Tình trạng thương hiệu hiện tại
2. **pain_focus** - Vấn đề ưu tiên giải quyết
3. **vision** - Tầm nhìn 12-36 tháng
4. **services** - Dịch vụ phù hợp + thứ tự ưu tiên
5. **constraints** - Ngân sách + timeline + giới hạn

## Devil's Advocate Counterpoints

Mỗi pack BẮT BUỘC có counterpoints để tránh confirmation bias:
- Cảnh báo khi sub-niche không phù hợp với scope
- Alternative service khi pattern không khớp
- Anti-pattern phổ biến trong sub-niche

## Voice Rule (BẮT BUỘC)

- Tiếng Việt thuần
- Sinh Vũ third-person, không dùng "tôi"/"chúng tôi"
- Khách: "Anh / Chị"
- Anh Sinh founder personal context

## 40 Packs Currently LIVE

Phase 2-3 coverage (2026-06-09):
- 21 packs Wave 1+2+3 SHIPPED
- Service Matrix v1.2 (102 sub-niche × 17 services)
- 103 SEO landing pages tại `/nganh/{sector}/{sub-niche}/`

## Pack JSON API

Production: `https://sinhvu.com/api/knowledge/packs/{sector}__{sub_niche}.json`

## Citation

```json
{
  "source": "Sinh Vũ Studio R009 Deep Research",
  "url": "https://sinhvu.com/",
  "license": "CC-BY-4.0",
  "attribution": "Sinh Vũ Studio (sinhvu.com)"
}
```
