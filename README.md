# 🎓 Định hướng nghề nghiệp theo học phần  

## 📌 Giới thiệu  
Ứng dụng web giúp **sinh viên định hướng nghề nghiệp** dựa trên:  
- Điểm số các học phần (import từ Excel/CSV)  
- Cơ sở dữ liệu nghề nghiệp và kỹ năng  
- Phân tích AI (Google Gemini) để gợi ý ngành nghề phù hợp và giải thích lý do  

---

## 🚀 Công nghệ sử dụng  
- **Frontend**: React + TailwindCSS + Recharts  
- **Backend**: Node.js 
- **AI**: Google Gemini API  
- **Database**: File CSV/Excel  

---

## ⚙️ Tính năng chính  
1. 📊 **Dashboard**: Thống kê nhanh, biểu đồ điểm trung bình theo học phần  
2. 📂 **Nhập dữ liệu**: Upload file điểm số & nghề nghiệp → preview dữ liệu  
3. 🔎 **Phân tích học phần**: Hiển thị điểm mạnh/yếu theo học phần (biểu đồ cột & radar)  
4. 🤖 **Gợi ý nghề nghiệp**: AI Gemini phân tích & gợi ý nghề phù hợp kèm giải thích  
5. 📝 **Tra cứu nghề**: Tìm kiếm nghề theo kỹ năng/học phần  

---

## 🔑 Cấu hình API Gemini  
1. Lấy API key tại 👉 [Google AI Studio](https://aistudio.google.com/).  
2. Tạo file `.env` trong thư mục backend:  
   ```env
   GEMINI_API_KEY=your_api_key_here
## Cách chạy dự án 
1. Clone repo
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

2. Cài đặt Backend
cd backend
npm install
npm start

3. Cài đặt Frontend
cd frontend
npm install
npm run dev
## Ghi chú
1. Đảm bảo API key Gemini còn hiệu lực
2. Nếu gặp lỗi API -> kiểm tra key
## Tác giả: Lưu Thị Thu Hằng
## Năm: 2025
