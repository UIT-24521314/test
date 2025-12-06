# Tetris
# Đồ án cuối kỳ môn học SS006 - Kỹ năng nghề nghiệp: Thiết kế game Tetris
Đây là đồ án cuối kỳ tái hiện lại trò chơi xếp gạch cổ điển (Tetris), được viết bằng ngôn ngữ C++

# 🎮 Tetris Game Implementation - Computer Science Project

![C++](https://img.shields.io/badge/Language-C%2B%2B17-blue?style=for-the-badge&logo=c%2B%2B)
![SDL2](https://img.shields.io/badge/Library-SDL2%20%2F%20SFML-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **Đồ án môn học:** Kỹ năng nghề nghiệp - Thiết kế game\
> **Chủ đề:** Triển khai trò chơi xếp gạch cổ điển (Tetris Game Clone)

---

## 📑 Mục lục
1. [Giới thiệu](#-giới-thiệu)
2. [Cơ sở Toán học & Thuật toán](#-cơ-sở-toán-học--thuật-toán)
3. [Cấu trúc dự án](#-cấu-trúc-dự-án)
4. [Cài đặt & Hướng dẫn sử dụng](#-cài-đặt--hướng-dẫn-sử-dụng)
5. [Kết quả mô phỏng](#-kết-quả-mô-phỏng)
6. [Thành viên thực hiện](#-thành-viên-thực-hiện)
7. [Tài liệu tham khảo](#-tài-liệu-tham-khảo)

---

## 📖 Giới thiệu

**Tetris** là một trò chơi giải đố sắp xếp gạch (Tile-matching video game) kinh điển. Mục tiêu của trò chơi là di chuyển và xoay các khối gạch (Tetrominoes) đang rơi xuống để tạo thành các hàng ngang lấp đầy và xóa chúng.

**🎯 Mục tiêu của đồ án:**
* Áp dụng kiến thức về Mảng 2 chiều (2D Array) để quản lý lưới trò chơi (Grid).
* Cài đặt thuật toán biến đổi hình học (Geometric Transformation) để xử lý xoay khối.
* ...

---

## 📐 Cơ sở Toán học & Thuật toán

Trò chơi được xây dựng dựa trên hệ tọa độ Descartes và các ma trận biểu diễn trạng thái.

### 1. Hệ tọa độ và Ma trận xoay (Rotation Matrix)
Các khối Tetromino được biểu diễn trong một ma trận cục bộ. Để xoay một điểm $(x, y)$ một góc $90^\circ$ theo chiều kim đồng hồ quanh gốc tọa độ, ta áp dụng công thức biến đổi tuyến tính:

* **Công thức tổng quát:**
....

* **Với góc $\theta = 90^\circ$ (trong hệ tọa độ màn hình máy tính):**
....

### 2. Phát hiện va chạm (Collision Detection)
Thuật toán kiểm tra tính hợp lệ của nước đi (Next Move Validity). Một vị trí $(x, y)$ của khối gạch được coi là hợp lệ nếu thỏa mãn:

...

### 3. Hệ thống tính điểm (Scoring Algorithm)
Điểm số ($S$) được tính dựa trên số hàng ($n$) xóa được cùng một lúc (Combo):

...

---
## 📂 Cấu trúc dự án

## Cài đặt & Hướng dẫn sử dụng

Yêu cầu hệ thống:
...

🎮 Điều khiển\
...

## 📊 Kết quả mô phỏng

👥 Thành viên thực hiện 
<div align="center">

| STT |   MSSV   |      Họ và tên         | 
|:---:|:--------:| ---------------------  |
|  1  | 23521128 | Nguyễn Thị Quỳnh Như   |
|  2  | 24521314 | Nguyễn Văn Phát        |
|  3  | 24521381 | Lê Văn Hữu Phúc        |
|  4  | 24521344 | Thái Hoàng Huy Phong   |
|  5  | 24521175 | Dương Phạm Trần Nguyễn |

</div>

## 📚 Tài liệu tham khảo

1. Wikipedia, "Tetris - Game Logic and Rules", [Online]. Available: https://en.wikipedia.org/wiki/Tetris
2. Game Programming Patterns, "The Game Loop".
3. Super Rotation System (SRS) Documentation for standard Tetris rotation rules.

Copyright © 2025 - Khoa Khoa học Máy tính, Đại học Công nghệ Thông tin, Đai học Quốc gia Thành phố Hồ Chí Minh
