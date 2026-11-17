<p align="center">
  <img src="docs/icon.png" width="128" height="128" alt="Biểu tượng Cicada">
</p>

<h1 align="center">Cicada · 知了</h1>

<p align="center">
  Mọi cuộc gọi. Mọi buổi livestream. Không còn rào cản ngôn ngữ.<br>
  Nghe hiểu, nói lại và ghi nhớ tất cả. Ghi chú cuộc họp trực tiếp, bản ghi song ngữ, phụ đề và phiên dịch trên Mac, Windows, Linux và Android.
</p>

<p align="center">
  <a href="https://cicada.indaloop.app"><img src="https://img.shields.io/badge/Website-cicada.indaloop.app-E8552B?style=for-the-badge" alt="Website: cicada.indaloop.app" height="36"></a>
  &nbsp;
  <a href="https://cicada.indaloop.app/en/download/"><img src="https://img.shields.io/badge/T%E1%BA%A3i%20v%E1%BB%81-Mac%20·%20Windows%20·%20Linux%20·%20Android-15171C?style=for-the-badge" alt="Tải về cho Mac, Windows, Linux và Android" height="36"></a>
  &nbsp;
  <a href="https://x.com/wquguru"><img src="https://img.shields.io/badge/Follow-@wquguru-000000?style=for-the-badge&logo=x&logoColor=white" alt="Theo dõi @wquguru trên X" height="36"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-14.4%2B-black" alt="macOS 14.4+">
  <img src="https://img.shields.io/badge/Windows-10%202004%2B-black" alt="Windows 10 2004+">
  <img src="https://img.shields.io/badge/Ubuntu-22.04%2B-black" alt="Ubuntu 22.04+">
  <img src="https://img.shields.io/badge/Android-10%2B-black" alt="Android 10+">
  <img src="https://img.shields.io/badge/license-Apache--2.0-blue" alt="Apache-2.0">
</p>

<p align="center">⭐ Nếu thấy hữu ích, hãy star repo này để sau còn tìm lại</p>

<p align="center"><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.vi.md">Tiếng Việt</a></p>

Trong cuộc họp hay buổi livestream, Cicada hiện phụ đề song ngữ trực tiếp và vừa nghe vừa viết ghi chú cuộc họp có cấu trúc. Đến lượt bạn nói, giữ phím nói (`⌥` bên phải trên Mac, `Ctrl` bên phải trên Windows, có thể đổi) rồi nói — phía bên kia nghe giọng bạn đã được dịch ngay trong cuộc gọi. Cicada nghe trực tiếp âm thanh hệ thống, không cần đưa bot vào cuộc họp, nên không ai nhận ra. Trên Mac chip Apple, toàn bộ nhận dạng giọng nói chạy trên máy, âm thanh không rời khỏi máy tính của bạn.

**Dùng được ở đâu**: Mọi thứ phát ra tiếng trên máy tính — Tencent Meeting, Feishu, DingTalk, WeCom, Zoom, Teams, Google Meet, Webex, Discord, cuộc gọi thoại Telegram, cùng X Spaces, YouTube, Twitch, Bilibili Live, podcast và trang web. Trên điện thoại, hệ thống chặn ghi âm từ ứng dụng gọi điện và họp — hãy bật loa ngoài và dùng chế độ **In person**.

<p align="center">
  <img src="docs/demo.gif" width="800" alt="Livestream tiếng Anh của Bloomberg trên YouTube, bên phải là ghi chú tiếng Trung trực tiếp, chủ đề và sơ đồ xương cá của Cicada, bên dưới là phụ đề song ngữ">
</p>

## Nền tảng

| Nền tảng | Yêu cầu | Ghi chú |
|---|---|---|
| Mac | macOS 14.4+, chip Apple / Intel | Đầy đủ tính năng. Chip Apple nhận dạng trên máy (không cần key); Intel cần Ling key (giọng nói do Ming nhận dạng) |
| Windows | Windows 10 2004+, x64 / ARM64 | Cần key dịch vụ AI (Ling, OpenRouter, ZenMux…); xem [windows/](windows/README.md) |
| Linux | Ubuntu 22.04 / 24.04 desktop | Cần key dịch vụ AI; cửa sổ ghi chú hiện khi chia sẻ màn hình; xem [linux/](linux/README.md) |
| Android | Android 10+ | Cần key dịch vụ AI; phụ đề cho video và livestream, phiên dịch trực tiếp mặt đối mặt; xem [android/](android/README.md) |

Bộ cài có trên [trang tải về](https://cicada.indaloop.app/en/download/) và [Releases](https://github.com/wquguru/cicada/releases). Cả bốn nền tảng dùng chung số phiên bản và định dạng bản ghi cuộc họp. Các phần dưới đây lấy ứng dụng Mac làm ví dụ.

## Tính năng

### Ghi chú trực tiếp và bản ghi song ngữ

Trong lúc nghe, Cicada sắp xếp tóm tắt, chủ đề và ý chính, kết luận, việc cần làm, sơ đồ xương cá và bảng thuật ngữ tên riêng. Bấm vào kết luận hay việc cần làm bất kỳ để nhảy về đúng đoạn gốc. Nhấn `⌘F` để tìm — kể cả từ đồng âm bị nhận dạng sai cũng tìm ra.

Khi đã kết nối dịch vụ AI, tên riêng và thuật ngữ nghe sai được sửa ngay: từ đồng âm sửa luôn, tên lạ hỏi bạn một lần, xác nhận xong sẽ tự sửa. Có thể dán sẵn thuật ngữ hay dùng vào **Word list** trong Settings. Sau cuộc họp, chọn **Edit line…** để sửa hàng loạt cùng một từ nghe sai trong cả phiên, có thể hoàn tác đầy đủ.

### Phụ đề trực tiếp và nhận diện ngôn ngữ

Cicada nhận ra ngôn ngữ đang nói trong vài giây và dịch sang ngôn ngữ hệ thống của bạn; nhấn `⌃⌥S` để đổi chế độ hiển thị. Thanh phụ đề chỉ hiện khi có người nói và trở nên trong suốt khi rê chuột qua để không vướng. Trên macOS 26 với chip Apple, Cicada còn nghe lại trên máy để chỉnh từng câu sau 15 đến 30 giây, sửa lỗi chính tả và từ bị sót.

### Họp trực tiếp và họp kết hợp

Bấm **Turn on mic** để thu tiếng người nói trong phòng. Họp kết hợp dùng chung nút này: âm thanh máy tính được đánh dấu **Online**, âm thanh micro đánh dấu **In room**, gộp vào một bản ghi (trên macOS 14 và 15, bật micro thì chỉ nghe phòng họp). Khi dùng loa ngoài, Cicada tự loại bỏ âm trùng; khi đeo tai nghe, hai bên có thể nói cùng lúc và đều được giữ lại. Windows và Linux theo cùng quy tắc.

Trên Mac, mũi tên nhỏ cạnh nút cho phép chọn micro (ví dụ iPhone hoặc micro hội nghị) mà không đổi micro mặc định của hệ thống. Những gì micro nghe được chỉ vào ghi chú, không bao giờ vào cuộc họp; muốn phía bên kia nghe bạn, hãy dùng phiên dịch đồng thời bên dưới.

### Phiên dịch đồng thời

Giữ phím `⌥` bên phải và nói, phía bên kia sẽ nghe giọng bạn đã được dịch trong ứng dụng họp.

Trên Mac, bạn cũng có thể bật **Hands-free** trong **Settings › Interpreting**: khi đang nghe cuộc họp, chỉ cần bắt đầu nói, âm thanh cuộc họp tự nhỏ lại, giọng đã dịch được gửi đi sau 1 giây ngừng nói. Chế độ này tạm dừng khi micro đang bật; khi có người khác ở gần, nên chuyển lại phím nói để giọng họ không bị nhầm là của bạn.

Bật phiên dịch sẽ chuyển micro hệ thống sang BlackHole 2ch, một driver ảo tải và cài bằng một cú bấm. Có Ling API key, bạn dùng được giọng tự nhiên hoặc nhân bản giọng mình từ bản ghi 8 đến 30 giây; không có key vẫn dùng được giọng có sẵn của macOS. Phiên dịch trên Windows và Linux, cùng **In person** trên Android, cũng dùng được giọng của bạn, nhân bản từ bản ghi 10 đến 15 giây với Ling key.

<p align="center">
  <img src="docs/interpreting.png" width="640" alt="Cài đặt phiên dịch: phím nói Option bên phải, ngôn ngữ đích, nghe thử giọng Ming và giọng macOS">
</p>

### Bản ghi cuộc họp

Bản ghi song ngữ, ghi chú và file ghi âm gốc được lưu trên thiết bị. Bấm vào dòng bất kỳ để phát từ đó, chữ được tô sáng và cuộn theo. Mô hình giọng nói trên máy tự tách người nói (và điền tên khi đã có Ling key); có thể đổi tên hoặc gộp bất cứ lúc nào nếu nhận nhầm. Trên Mac, đặt tên cho người nói rồi bấm **Remember this voice** (hãy hỏi ý họ trước), các cuộc họp sau sẽ nhận ra họ; mẫu giọng chỉ nằm trên máy Mac này, quản lý hoặc xoá trong **Settings › General › Remember speakers**. Hiện tại "bạn" trong bản ghi chỉ gồm những gì bạn nói khi giữ phím nói; ghi lại lời bạn nói trực tiếp trong cuộc họp nằm trong [lộ trình](#lộ-trình).

Sau cuộc họp, bạn có thể tạo ghi chú bù, bấm vào tóm tắt, kết luận hay việc cần làm trong cửa sổ chính để sửa tại chỗ, dùng **Transcribe Again** trên file ghi âm nếu chọn nhầm ngôn ngữ, xuất ra Markdown, Word và phụ đề SRT, hoặc chuyển file âm thanh / video có sẵn thành văn bản qua **File › Import Recording or Video…**. Trên Mac, **Copy Notes** (⇧⌘C) dán vào Feishu, Notion hay Word kèm tiêu đề, danh sách và hình sơ đồ xương cá, còn dán vào khung chat thì ở dạng Markdown. Bật **Settings › General › Save to folder** thì mỗi cuộc họp cũng tự lưu dạng Markdown (có frontmatter ở đầu cho agent) vào vault Obsidian hoặc thư mục khác, tự cập nhật khi bạn đổi tên hay tạo lại ghi chú.

Bấm **Share…** để tạo đường link tới ghi chú (có thể kèm toàn bộ bản ghi song ngữ), có thời hạn và mật khẩu; trước khi tải lên, ứng dụng tự chặn key, thông tin công ty chưa công bố và nội dung nhạy cảm khác.

<p align="center">
  <img src="docs/records.png" width="640" alt="Cửa sổ bản ghi cuộc họp với người nói đã được nhận diện và bản ghi Anh – Trung từng dòng">
</p>

## Quyền riêng tư và quyền truy cập

**Mac chip Apple**: Ghi âm và nhận dạng giọng nói chạy trên máy, âm thanh không rời khỏi máy. Chỉ phần văn bản đã nhận dạng được gửi đi (để dịch và viết ghi chú). Ngoại lệ: những câu bạn nói khi phiên dịch có cấu hình Ling key, khi bấm **Use Ling for Now**, hoặc khi chuyển sang dịch vụ tự host trong **Settings › AI Service** — khi đó âm thanh được gửi tới dịch vụ tương ứng. Không có API key, phụ đề trực tiếp, dịch, bản ghi cuộc họp và phiên dịch đều miễn phí. Ghi chú trực tiếp, dịch giọng nói một bước và nhân bản giọng cần Ling API key của riêng bạn (Ling là dịch vụ LLM của Ant Group). Một giờ họp tốn khoảng ¥0,15 đến ¥1 (nhân dân tệ), và Ling tặng ¥10 mỗi tháng, đủ cho 10 đến 50 giờ.

**Mac Intel, Windows, Linux, Android**: Nhận dạng giọng nói chạy trên đám mây và cần key dịch vụ AI; âm thanh được gửi từng đoạn tới Ming của Ling hoặc dịch vụ bạn chọn (OpenRouter, ZenMux…). File ghi âm và bản ghi cuộc họp vẫn chỉ nằm trên thiết bị của bạn.

Ứng dụng Mac chỉ xin quyền khi bạn dùng tính năng tương ứng; từ chối thì mọi thứ khác vẫn chạy bình thường:

| Quyền | Dùng để | Nếu không cấp |
|---|---|---|
| Ghi âm thanh hệ thống (Screen & System Audio Recording) | Nghe âm thanh hệ thống để làm phụ đề; không bao giờ ghi màn hình | Phụ đề và ghi chú không hoạt động |
| Microphone | Giữ để nói hoặc **Hands-free** khi phiên dịch; bấm **Turn on mic** để nghe phòng họp | Không nói để dịch được, không nghe được phòng họp |
| Input Monitoring | Nhận phím `⌥` bên phải (không chặn hay ghi lại phím khác) | Đổi sang phím tắt `⌃`/`⌘` để khỏi cần quyền này |
| Mật khẩu quản trị | Cài micro ảo BlackHole 2ch (hỏi một lần) | Phía bên kia không nghe được phiên dịch; mọi thứ khác vẫn chạy |

- **Kết nối mạng minh bạch**: Chỉ kết nối Internet để dịch (`translate.googleapis.com`), tới dịch vụ AI bạn cấu hình (như `api.ant-ling.com`), tải driver BlackHole đã được Apple notarize (kiểm tra SHA-256), và kiểm tra bản cập nhật trên GitHub mỗi ngày một lần. Không analytics, không theo dõi, không có máy chủ riêng.
- **Lưu trữ trên máy**: Bản ghi và file ghi âm nằm ở `~/Library/Application Support/LiveSubs`. Key và mẫu giọng chỉ tài khoản hệ thống hiện tại đọc được, và không có trong Time Machine hay log.
- **Ẩn khỏi chụp màn hình**: Trên Mac, chia sẻ màn hình, quay màn hình và chụp màn hình đều không bắt được cửa sổ ghi chú. Có thể bật thủ công **Show in screen sharing** khi quay demo.

## Mô hình

Bảng dưới là cấu hình trên Mac chip Apple. Khi dùng dịch vụ tự host (**Other (OpenAI-compatible)**), có thể bật **Send audio and text only to your service** trong **Settings › AI Service** để bỏ hẳn Google.

| Tính năng | Có Ling key | Không có key / dự phòng |
|---|---|---|
| Nhận dạng giọng nói và nhận diện ngôn ngữ | Apple `SpeechAnalyzer` / `SpeechTranscriber` (trên máy); macOS 14.4–15 dùng `SFSpeechRecognizer` (trên máy, cần Dictation) | Như bên trái |
| Dịch câu đã nói xong | Ling `Ling-3.1-flash` (đổi được sang `Ling-3.0-flash` trong Settings › AI Service) | Google Translate → Apple `Translation` (trên máy, chỉ macOS 26) |
| Dịch câu đang nói dở | Google Translate | Hiện nguyên văn cho tới khi có bản dịch cả câu |
| Ghi chú trực tiếp và bản đầy đủ sau cuộc họp | Ling `Ling-3.1-flash` | Không có |
| Kiểm tra key có dùng được không | Ling `Ling-3.0-tiny` (1 token) | — |
| Phiên dịch: nghe và dịch | Ming `Ming-3.0-audio-flash` (một bước) | Nhận dạng trên máy của Apple + chuỗi dịch ở trên |
| Phiên dịch: phát giọng và nhân bản giọng | Ming `Ming-3.0-tts-0.5B` | Giọng có sẵn của Mac (`AVSpeechSynthesizer`), không nhân bản |
| Nhận diện người nói | WeSpeaker ResNet34-LM (đóng gói sẵn, chạy trên máy qua Core ML) | Như bên trái |

## Cài đặt Ling API key

1. Đăng ký và đăng nhập [nền tảng mở Ling](https://chat.ant-ling.com/platform/api), tạo token và sao chép key bắt đầu bằng `sk-`.
2. Mở **Settings › AI Service** trong Cicada (hoặc banner trên đầu cửa sổ ghi chú), dán key và lưu.

**Không đăng ký được Ling?** Ở góc trên bên phải **Settings › AI Service** (hoặc bấm **Can't use Ling?** trong phần hướng dẫn ban đầu), bạn có thể chuyển sang OpenRouter, ZenMux, OpenAI hoặc bất kỳ dịch vụ tương thích OpenAI nào (kể cả dịch vụ cục bộ hay trong mạng LAN như Ollama, vLLM, SGLang, Qwen3-ASR và Whisper).

Sau khi chuyển, ghi chú trực tiếp và dịch cả câu vẫn chạy, OpenRouter và ZenMux còn dùng được giọng Gemini tự nhiên cho phiên dịch; dịch giọng nói một bước và nhân bản giọng chỉ Ling hỗ trợ. Với dịch vụ tự host, ghi chú và đặt tên người nói có thể dùng mô hình mạnh hơn riêng, hoặc kết nối tới dịch vụ khác (nhập địa chỉ và key riêng); tìm mô hình trong danh sách, hoặc gõ trực tiếp nếu không thấy. Khi Windows, Linux hay Android chuyển sang dịch vụ khác, phần nghe phía bên kia cũng đi qua dịch vụ mới, nên phụ đề chậm hơn Ling 1–2 giây. Nếu kết nối lỗi, Settings sẽ nói rõ là do key, mô hình hay proxy (chi tiết về proxy xem [trang cài đặt](https://cicada.indaloop.app/en/start/#proxy)).

## Yêu cầu và cài đặt

Bộ cài có trên [trang Releases](https://github.com/wquguru/cicada/releases/latest) và [website](https://cicada.indaloop.app); có thể đối chiếu SHA-256 với `checksums.txt` trong Releases. Có thắc mắc, liên hệ tác giả [@wquguru](https://x.com/wquguru) trên X.

### Mac

Cần macOS 14.4+ (chip Apple và Intel). Trên chip Apple với macOS 14.4–15, trước tiên vào **System Settings › Keyboard** bật **Dictation** và thêm các ngôn ngữ muốn nghe; macOS 26 dùng thẳng mô hình mới trên máy, không cần Dictation; Mac Intel dùng nhận dạng Ming trên đám mây và cần Ling key.

Tải `Cicada-<version>-macOS-AppleSilicon.dmg` hoặc `Cicada-<version>-macOS-Intel.dmg` rồi kéo Cicada vào Applications (kiểm tra bằng `shasum -a 256 Cicada-*.dmg`). Ứng dụng chưa được Apple notarize, nên nếu lần mở đầu bị chặn, vào **System Settings › Privacy & Security** và bấm **Open Anyway**. Làm theo hướng dẫn ban đầu để cấp quyền và thử cuộc họp mẫu.

<p align="center">
  <img src="docs/onboarding.png" width="640" alt="Bước 2 của hướng dẫn ban đầu phát cuộc họp mẫu hai người kèm phụ đề song ngữ trực tiếp">
</p>

### Windows

Cần Windows 10 2004+ (x64 hoặc Snapdragon ARM64). Tải bộ cài và bấm đúp để cài, không cần quyền quản trị. Nếu SmartScreen chặn, bấm **More info › Run anyway**. Khi dùng phiên dịch, phần hướng dẫn sẽ giúp bạn cài micro ảo VB-Cable miễn phí.

### Linux

Cần Ubuntu 22.04 hoặc 24.04 desktop (x86_64 hoặc arm64). Tải `Cicada-<version>-Linux.tar.gz` và chạy `tar xzf Cicada-<version>-Linux.tar.gz && cicada-linux/install.sh` trong terminal. Phiên dịch tự tạo "Cicada Microphone", không cần cài driver. Cửa sổ trên Linux không ẩn được khỏi chia sẻ màn hình, nên cửa sổ ghi chú sẽ báo là đang hiện khi bạn chia sẻ màn hình. Để bật **Settings › General › Save meeting audio**, cần cài định dạng media bên thứ ba của hệ thống (như `ubuntu-restricted-extras`) để có bộ mã hoá AAC. Bật **Settings › Word list › Fix misheard words live** sẽ gửi thêm một request văn bản cho mỗi câu.

### Android

Cần Android 10+. Tải và cài `Cicada-<version>-Android.apk`; trên Android 15 trở lên, lần đầu bật phụ đề nổi cần cho phép cài đặt bị hạn chế trong App info. Ứng dụng cũng có mẫu giọng trên máy để tách người nói và sửa từ nghe sai ngay khi đang nghe. Ứng dụng gọi điện và họp chặn thu âm nội bộ trên Android — chỉ cần bật loa ngoài cho cuộc gọi và chuyển sang **In person**.

## Lộ trình

Xếp gần theo thứ tự ưu tiên; cứ mở Issue cho thứ bạn muốn có. Chi tiết xem [docs/ROADMAP.md](docs/ROADMAP.md).

- **Ghi lại lời của chính mình**: Nghe micro liên tục có khử tiếng vọng trong cuộc họp, để lời bạn nói trực tiếp cũng vào bản ghi và ghi chú.
- **Ký mã và notarize**: Ký và notarize chính thức bộ cài Mac và Windows để hết cảnh báo bảo mật, và đưa key AI về lại keychain của hệ thống.
- **Nhận diện người nói trên các nền tảng khác**: Mac đã nhớ giọng đồng nghiệp thường gặp và nhận ra họ ở các cuộc họp sau; tiếp theo là Windows, Linux và Android.
- **Ghi chú không cần key**: Tạo ghi chú cuộc họp trên các máy Mac được hỗ trợ bằng mô hình trên máy của Apple.
- **Android trên chợ ứng dụng**: Không phải cài APK thủ công nữa.
- **iPhone và iPad**: Bắt đầu với nghe phòng họp, phiên dịch mặt đối mặt và bản ghi cuộc họp.

## Gỡ cài đặt

Thoát Cicada và kéo nó từ thư mục Applications vào Thùng rác. Bản ghi và file ghi âm nằm ở `~/Library/Application Support/LiveSubs`, có thể xoá thủ công nếu không cần. Để xoá cài đặt, chạy:

```bash
defaults delete com.wquguru.cicada
```

## Phát triển

Ứng dụng Mac chỉ cần Xcode Command Line Tools (`xcode-select --install`) và không có phụ thuộc bên thứ ba. Trên macOS 27, nếu báo thiếu `SwiftUIMacros`, hãy cài Xcode đầy đủ và chạy `sudo xcode-select -s /Applications/Xcode.app`. Build trên các nền tảng khác xem [windows/README.md](windows/README.md), [linux/README.md](linux/README.md) và [android/README.md](android/README.md).

```bash
scripts/build.sh            # dev build → build/Cicada.app ("Cicada Dev", runs alongside the release app)
open build/Cicada.app
scripts/package.sh          # package release DMG, zip, and SHA-256 checksums
```

Kiến trúc mã xem [AGENTS.md](AGENTS.md). Mã nguồn website nằm trong `site/` (sinh bởi `scripts/site.py`), lịch sử phát hành ở [CHANGELOG.md](CHANGELOG.md) hoặc [nhật ký thay đổi trên website](https://cicada.indaloop.app/changelog/).

## Giấy phép

Dự án dùng giấy phép [Apache-2.0](LICENSE). Driver micro ảo BlackHole 2ch dùng giấy phép GPL; nó không được đóng gói trong bộ cài mà được tải từ địa chỉ chính thức khi bạn bấm cài. Mô hình giọng nói đóng gói sẵn là ResNet34-LM của [WeSpeaker](https://github.com/wenet-e2e/wespeaker) huấn luyện trên VoxCeleb (CC BY 4.0), được chuyển sang Core ML bằng `scripts/convert-voiceprint.py`.
