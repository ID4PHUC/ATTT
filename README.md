# 🖧 Ứng Dụng Trắc Nghiệm Client-Server (Multi Client)

## 📚 Môn học: Lập trình mạng


**Sinh viên thực hiện:** Dương Hoàng Phúc

**Sinh viên thực hiện:** Trần Trọng Phúc

**Sinh viên thực hiện:** Nguyễn Duy Nhất

**Sinh viên thực hiện:** Phạm Huy Hoàng

**Sinh viên thực hiện:** Nguyễn Bảo Kha


---

## ⚙️ Công nghệ sử dụng
- 💻 Ngôn ngữ: C# (.NET Framework)
- 🔌 Mô hình: Multi Client – Server (Socket TCP/IP)
- 🗄️ Cơ sở dữ liệu: SQL Server 2019
- 🖥️ Giao diện: WPF

---

## 🧠 Mô tả chức năng chính

### 📤 SERVER
- Gửi câu hỏi cho tất cả các client đang kết nối
- Nhận câu trả lời và tính điểm
- Hiển thị bảng xếp hạng cuối buổi thi

### 📥 CLIENT
- Giao diện đăng nhập, tham gia thi
- Hiển thị câu hỏi, chọn đáp án
- Hiển thị điểm sau mỗi câu hỏi và tổng kết

---

## 🗂️ Cấu trúc thư mục

```bash
APPTN/
│
├── ServerTN/         # Dự án WPF server
│   ├── MainWindow.xaml
│   └── ...
│
├── ClientTN/         # Dự án WPF client
│   ├── MainWindow.xaml
│   └── ...
│
├── SQL_docx/         # Tài liệu thiết kế CSDL
│   └── SQL.docx
└── README.md
