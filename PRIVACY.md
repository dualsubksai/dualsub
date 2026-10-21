# DualSub for All – Privacy Policy / Chính sách quyền riêng tư

_Last updated: 2026-10-19_

**English below. Tiếng Việt ở trên.**

---

## Tiếng Việt

DualSub for All ("Extension") là công cụ học ngoại ngữ chạy trong trình duyệt. Chính sách này mô tả dữ liệu Extension xử lý và cách xử lý.

### Dữ liệu Extension xử lý

1. **Từ và câu bạn tra cứu.** Khi bạn rê chuột lên một từ, bôi đen một đoạn, hoặc lưu một từ, Extension gửi từ/đoạn đó (và câu chứa nó khi lưu) tới dịch vụ dịch để lấy nghĩa. Yêu cầu được gửi trực tiếp từ trình duyệt của bạn tới dịch vụ dịch máy; khi dịch vụ đó không phản hồi, Extension gửi qua máy chủ DualSub, máy chủ chuyển tiếp tới nhà cung cấp dịch (DeepL hoặc Google) và không lưu nội dung. Không gửi kèm thông tin định danh cá nhân.
2. **Phụ đề video.** Trên YouTube, Extension tải phụ đề của video đang xem trực tiếp từ YouTube, giống như trình phát YouTube làm. Extension không gửi phụ đề đi đâu khác.
3. **Sổ từ vựng.** Từ đã lưu, câu ví dụ, ghi chú, kết quả phân tích, tên và link nguồn (video, trang web, file PDF) được lưu **cục bộ trên máy bạn** trong bộ nhớ của trình duyệt (`chrome.storage.local`). Extension không tải sổ từ vựng lên bất kỳ máy chủ nào, trừ khi bạn tự bấm "Sao lưu JSON" để tải file về máy mình.
4. **Cài đặt.** Tùy chọn hiển thị (ngôn ngữ, cỡ chữ, chế độ đọc…) được lưu qua `chrome.storage.sync`, do Chrome đồng bộ theo tài khoản Google của bạn nếu bạn bật đồng bộ.
5. **API key AI (tùy chọn).** Nếu bạn tự nhập API key của Google Gemini, OpenAI hoặc Anthropic, key được lưu cục bộ trên máy (`chrome.storage.local`) và chỉ được gửi tới đúng nhà cung cấp đó khi bạn yêu cầu phân tích một từ. Khi bạn dùng tính năng AI qua máy chủ DualSub (gói Pro), từ và câu ví dụ được gửi tới máy chủ DualSub, máy chủ chuyển tiếp tới nhà cung cấp AI (Anthropic hoặc Google) và trả kết quả về; máy chủ không lưu nội dung này.
6. **License key (gói Pro).** Nếu bạn nhập license key, Extension gửi key tới máy chủ DualSub để xác thực với nhà cung cấp thanh toán. Extension không nhận hay lưu thông tin thẻ/thanh toán; việc thanh toán diễn ra trên trang của nhà cung cấp thanh toán.
7. **Nội dung trang web và file PDF.** Chế độ đọc web và trình đọc PDF xử lý nội dung trang ngay trên máy bạn để xác định từ dưới con trỏ. Nội dung trang/file không được gửi đi, ngoài từ hoặc đoạn bạn chủ động tra.
8. **Chat Mode (WhatsApp Web, Telegram Web, Messenger, Discord, Instagram Direct).** Khi bạn bật Chat Mode, Extension đọc nội dung các tin nhắn đang hiện trên màn hình tại các trang chat này và gửi **văn bản tin nhắn** (tin nhắn đến, và nội dung bạn đang gõ) tới dịch vụ dịch máy để lấy bản dịch, theo cùng cách như mục 1. Không gửi tên người gửi, số điện thoại hay thông tin tài khoản. Bản dịch chỉ hiển thị trên máy bạn, không được lưu. Chat Mode tắt mặc định; bạn bật trong popup và có thể tạm dừng cho từng cuộc trò chuyện. Extension không bao giờ tự gửi tin nhắn thay bạn.
9. **Thống kê sử dụng ẩn danh.** Để biết tính năng nào được dùng và cải thiện Extension, Extension đếm **số lượt** sử dụng theo ngày (ví dụ: số lần tra từ, lưu từ, dịch tin nhắn, mở Sổ từ vựng) và gửi tới máy chủ DualSub tối đa vài lần mỗi ngày, kèm một mã định danh ngẫu nhiên của bản cài (không liên kết với tài khoản, email hay thiết bị), phiên bản Extension, ngôn ngữ trình duyệt, ngày cài và trạng thái Pro. **Không** gửi từ bạn tra, nội dung tin nhắn, địa chỉ trang web hay bất kỳ nội dung nào. Dữ liệu được giữ 120 ngày. Bạn tắt tính năng này bất cứ lúc nào trong popup (*Gửi thống kê sử dụng ẩn danh*).

### Những gì Extension không làm

- Không thu thập lịch sử duyệt web, không theo dõi trang bạn xem.
- Không chứa quảng cáo, không chứa mã theo dõi (analytics) của bên thứ ba. Thống kê ẩn danh ở mục 9 do chính DualSub xử lý và tắt được.
- Không bán, cho thuê hay chia sẻ dữ liệu người dùng với bất kỳ ai.

### Quyền Extension yêu cầu và lý do

| Quyền | Lý do |
|---|---|
| `storage`, `unlimitedStorage` | Lưu cài đặt và sổ từ vựng trên máy; không giới hạn số từ. |
| Truy cập `youtube.com` | Đọc phụ đề video và hiển thị phụ đề song ngữ trên trình phát. |
| Truy cập mọi trang web (`<all_urls>`) | Chế độ đọc web: tra từ khi rê chuột trên trang bất kỳ. Chỉ hoạt động khi bạn bật chế độ này. |
| Truy cập `web.whatsapp.com`, `web.telegram.org`, `messenger.com`, `facebook.com/messages`, `discord.com`, `instagram.com/direct` | Chat Mode: dịch tin nhắn đến và nội dung bạn gõ. Chỉ hoạt động khi bạn bật Chat Mode. |
| Truy cập `translate.googleapis.com`, `generativelanguage.googleapis.com`, `api.openai.com`, `api.anthropic.com` | Gọi dịch vụ dịch và dịch vụ AI do bạn chọn. |
| `declarativeNetRequest`, `webNavigation` | Tự mở file PDF bằng trình đọc của Extension (tùy chọn, tắt được). |
| `contextMenus` | Menu chuột phải "Mở PDF này bằng DualSub". |

### Dịch vụ bên thứ ba

- Dịch vụ dịch máy (Google, DeepL) cho tra từ và dịch câu
- Google Gemini, OpenAI, Anthropic (phân tích ngữ pháp, nếu bạn bật)
- Nhà cung cấp thanh toán (gói Pro): Lemon Squeezy

Mỗi dịch vụ có chính sách quyền riêng tư riêng.

### Xóa dữ liệu

Gỡ Extension sẽ xóa toàn bộ sổ từ vựng, cài đặt và API key trên máy. Bạn cũng có thể xóa từng từ trong Sổ từ vựng.

### Liên hệ

Email: **dualsub.ksai@gmail.com**

---

## English

DualSub for All (the "Extension") is a language-learning tool that runs in your browser. This policy explains what data the Extension processes and how.

### Data the Extension processes

1. **Words and sentences you look up.** When you hover a word, select text, or save a word, the Extension sends that word/selection (and, when saving, the sentence it appears in) to a translation service to fetch its meaning. Requests go directly from your browser to a machine-translation service; if that service does not respond, the Extension sends the request through the DualSub server, which forwards it to a translation provider (DeepL or Google) and does not retain the content. No personally identifying information is attached.
2. **Video subtitles.** On YouTube, the Extension loads the current video's subtitles directly from YouTube, as the YouTube player itself does. Subtitles are not sent anywhere else.
3. **Vocabulary notebook.** Saved words, example sentences, notes, analysis results, and source names/links (video, web page, PDF) are stored **locally on your device** in browser storage (`chrome.storage.local`). The Extension never uploads your notebook to any server; "Backup JSON" only downloads a file to your own computer.
4. **Settings.** Display preferences are stored via `chrome.storage.sync`, which Chrome may sync with your Google account if you have sync enabled.
5. **AI API key (optional).** If you enter your own Google Gemini, OpenAI, or Anthropic API key, it is stored locally and sent only to that provider when you request an analysis. If you use the Pro AI feature via the DualSub server, the word and example sentence are sent to the DualSub server, which forwards them to the AI provider (Anthropic or Google) and returns the result; the server does not retain this content.
6. **License key (Pro).** If you enter a license key, the Extension sends it to the DualSub server for validation with the payment provider. The Extension never receives or stores card or payment details; payment happens on the payment provider's site.
7. **Web page and PDF content.** Reading mode and the PDF reader process page content on your device to find the word under the cursor. Page/file content is not transmitted, apart from the word or selection you explicitly look up.
8. **Chat Mode (WhatsApp Web, Telegram Web, Messenger, Discord, Instagram Direct).** When you turn on Chat Mode, the Extension reads the messages currently visible on these chat sites and sends the **message text** (incoming messages, and what you are typing) to the machine-translation service to obtain a translation, in the same way as item 1. Sender names, phone numbers and account details are not sent. Translations are shown on your device only and are not stored. Chat Mode is off by default; you enable it in the popup and can pause it per conversation. The Extension never sends messages on your behalf.
9. **Anonymous usage statistics.** To learn which features are used and improve the Extension, it counts **how many times** features are used per day (for example lookups, saved words, translated messages, notebook opens) and sends these counts to the DualSub server a few times a day, together with a random installation identifier (not linked to any account, email or device), the Extension version, browser language, install date and Pro status. It **never** sends the words you look up, message content, page URLs or any other content. Data is kept for 120 days. You can turn this off at any time in the popup (*Send anonymous usage statistics*).

### What the Extension does not do

- No browsing history collection, no tracking of pages you visit.
- No ads, no third-party analytics. The anonymous statistics in item 9 are processed by DualSub itself and can be switched off.
- No selling, renting, or sharing of user data.

### Permissions and why

| Permission | Reason |
|---|---|
| `storage`, `unlimitedStorage` | Store settings and the vocabulary notebook locally without a size cap. |
| Access to `youtube.com` | Read video subtitles and render dual subtitles on the player. |
| Access to all sites (`<all_urls>`) | Reading mode: hover-to-look-up on any page. Only active when you enable it. |
| Access to `web.whatsapp.com`, `web.telegram.org`, `messenger.com`, `facebook.com/messages`, `discord.com`, `instagram.com/direct` | Chat Mode: translate incoming messages and what you type. Only active when you enable Chat Mode. |
| Access to `translate.googleapis.com`, `generativelanguage.googleapis.com`, `api.openai.com`, `api.anthropic.com` | Call the translation and AI services you choose. |
| `declarativeNetRequest`, `webNavigation` | Open PDF files in the Extension's reader automatically (optional, can be turned off). |
| `contextMenus` | Right-click "Open this PDF with DualSub". |

### Third-party services

Machine-translation services (Google, DeepL); Google Gemini, OpenAI, Anthropic (optional AI analysis); Lemon Squeezy (Pro payments). Each has its own privacy policy.

### Data deletion

Uninstalling the Extension deletes the notebook, settings, and API keys on your device. Individual words can be deleted in the notebook.

### Contact

Email: **dualsub.ksai@gmail.com**
