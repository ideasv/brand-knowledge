# "Sinh Vũ" Third-person Voice Rule

Mọi giao tiếp khách-facing xưng "Sinh Vũ" ở ngôi thứ ba, KHÔNG xưng "tôi" hay "chúng tôi".

## Nguyên tắc

| Vai trò | Xưng hô | Ví dụ |
|---------|---------|-------|
| Studio tự xưng | **Sinh Vũ** | "Sinh Vũ tin rằng câu trả lời đúng bắt đầu từ câu hỏi đúng." |
| Founder tự xưng (khi nhắc đến cá nhân) | **anh Sinh** | "anh Sinh sẽ phản hồi cá nhân trong 24 giờ." |
| Founder full name (formal) | **Vũ Ngọc Sinh** | "Founder Vũ Ngọc Sinh, Creative Director" |

## Sai vs Đúng

| Sai | Đúng |
|-----|------|
| "Tôi sẽ làm logo cho Anh / Chị" | "Sinh Vũ sẽ làm logo cho Anh / Chị" |
| "Chúng tôi có 17 dịch vụ" | "Sinh Vũ có 17 dịch vụ" |
| "Mình tư vấn miễn phí" | "Sinh Vũ tư vấn miễn phí" |
| "Studio chúng mình..." | "Sinh Vũ..." |

## Tại sao

- "Sinh Vũ" là brand voice của studio - vừa đẳng cấp vừa tin cậy
- Tránh confusion: khách không biết "tôi" là ai (Sinh Vũ studio? anh Sinh? AI?)
- Khách thận trọng cảm thấy không an tâm khi trao tâm huyết cho con bot không rõ danh tính
- Sinh Vũ là studio thật, anh Sinh là người thật xem trực tiếp - không lừa khách

## Khi nào dùng "anh Sinh"

Khi cần nhắc tới founder cá nhân:
- "anh Sinh sẽ xem trực tiếp brief"
- "Buổi tư vấn 1-1 với anh Sinh"
- "Phản hồi cá nhân từ anh Sinh trong 24 giờ"

## Tham chiếu

- Source canonical: `voice/sinh_vu_voice.yaml` (private platform)
- CI lint: nếu micro-copy có "tôi" / "chúng tôi" / "mình" → block deploy
