#🔗 Nối Từ Helper 🇻🇳

An efficient, logic-based word-chaining tool designed as a Tampermonkey userscript. This tool automates or assists in word-link games directly in your browser using deterministic algorithms.

## ✨ Why this tool?
* **Zero AI Latency:** Unlike AI-based tools, this script uses local dictionary matching for near-instant responses.
* **Pure Logic:** Built with optimized JavaScript array/object mapping to find the best word connections.
* **Lightweight:** Runs directly in your browser via Tampermonkey without heavy dependencies.
* **Privacy-Focused:** No API calls to external AI servers. Everything stays in your browser.

## 🚀 Installation
1. Install the [Tampermonkey extension](https://www.tampermonkey.net/) for your browser.
2. Click **Create a new script** in the Tampermonkey dashboard.
3. Copy and paste the code from `wordchain.user.js` in this repository.
4. Save and refresh the game page.

## 🛠 Technical Details
This script ignores the "guesswork" of LLMs and focuses on **dictionary-driven logic**:
- **Scanning:** Monitors the game's DOM elements to detect the last word played.
- **Matching:** Filters through a pre-defined word list to find valid candidates.
- **Speed:** Sub-millisecond execution time.

## 📜 License
MIT License

* Nối Từ Helper là một Tampermonkey Userscript giúp bạn trở thành "bậc thầy" trong các trò chơi nối từ tiếng Việt. Thay vì dựa vào AI chậm chạp, script sử dụng thuật toán logic thuần túy và bộ từ điển tích hợp sẵn để đưa ra gợi ý ngay lập tức.

✨ Tính năng nổi bật
Gợi ý tức thì: Bôi đen một từ bất kỳ trên trang web, script sẽ hiển thị danh sách các từ có thể nối tiếp.
Hệ thống tự học (AI-Free Learning): Bạn có thể tự dạy script những từ mới. Những từ này sẽ được lưu trữ riêng và không bao giờ bị mất.
Giao diện Dark Mode: Thiết kế hiện đại, mượt mà với hiệu ứng neon và cực kỳ nhẹ.
Quản lý dữ liệu: Hỗ trợ Xuất/Nhập (Export/Import) từ điển cá nhân dưới dạng file JSON.
Hoạt động Offline: Không gửi dữ liệu ra bên ngoài, bảo mật tuyệt đối và tốc độ sub-millisecond.

🚀 Hướng dẫn cài đặt
Cài đặt tiện ích mở rộng Tampermonkey trên trình duyệt của bạn.
Nhấn vào biểu tượng Tampermonkey -> Bảng điều khiển (Dashboard).
Chọn tab Tiện ích mới (Create a new script).
Xóa hết code mặc định, copy toàn bộ code của Nối Từ Helper và dán vào.
Nhấn Ctrl + S để lưu.

🛠 Cách sử dụng
1. Lấy gợi ý từ
Bôi đen (Select) một từ hoặc một cụm từ trên bất kỳ trang web nào.
Một cửa sổ popup sẽ hiện ra ngay tại vị trí con trỏ chuột với danh sách các từ nối tiếp hợp lệ.
Click vào từ gợi ý: Để tự động sao chép (copy) từ đó vào bộ nhớ đệm.

2. Dạy từ mới
Nếu từ điển chưa có từ bạn cần, hãy nhập cụm từ mới vào ô "Dạy từ mới..." trong popup.
Nhấn Học hoặc phím Enter.
Các từ do bạn dạy sẽ có màu Xanh lá (🟢) để phân biệt với từ điển gốc.

3. Quản lý từ điển (Menu Command)
Nhấn vào biểu tượng Tampermonkey trên thanh công cụ trình duyệt.
Chọn dòng 🔗 Nối Từ — Quản lý từ điển.

Tại đây bạn có thể:
Xem thống kê số lượng từ gốc và từ đã học.
Xuất file JSON: Lưu lại "bí kíp" nối từ của riêng bạn.
Nhập file JSON: Đồng bộ từ điển từ thiết bị khác.
Xóa toàn bộ: Làm sạch từ điển cá nhân để học lại từ đầu.

⌨️ Phím tắt nhanh
Esc: Đóng nhanh cửa sổ gợi ý.
Enter: Xác nhận "Học" từ mới khi đang nhập liệu.
Click ra ngoài: Tự động ẩn popup.

📜 Giấy phép
Mã nguồn này được chia sẻ miễn phí cho cộng đồng yêu thích ngôn ngữ và lập trình.
