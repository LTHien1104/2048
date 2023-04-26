# 2048 
1.Mô tả
- Game kinh điển từng "làm mưa làm gió" những năm 14-15.
- Mục tiêu của trò chơi là trượt các khối vuông có mang số trên một lưới vuông để kết hợp chúng lại và tạo ra khối vuông có giá trị 2048.

2.Hướng dẫn cài đặt:
- Cách 1: Run & Build trên codeblock đã cài các thư viện SDL2,SDL_Mixer,SDL_ttf,SDL_image.
- Cách 2: Chạy file 2048.exe.

3.Cách chơi & luật chơi

3.1.Cách chơi
- Nhấn các phím W,A,S,D để di chuyển các ô số trên ma trận 4x4 để ghép 2 ô có giá trị giống nhau thành ô có giá trị gấp đôi.
hoặc
- Nhấn các phím mũi tên để di chuyển các ô số trên ma trận 4x4 để ghép 2 ô có giá trị giống nhau thành ô có giá trị gấp đôi.

3.2.Luật chơi
- Điều kiện thắng:Chơi tích lũy điểm đến số điểm cao nhất có thể.
- Điều kiện thua: Bàn cờ bị lấp đầy và không thể di chuyển được nữa.

4. Chức năng
- Có Hình ảnh, âm thanh,text
- High score.
- Save game.
- Pause game.
- Bổ sung bàn cờ rộng hơn đến 7x7.

5.Các kĩ thuật  
- Sử dụng nhiều nhất kĩ thuật liên quan đến mảng.
- Sử dụng các thư viện SDL_image,SDL_mixer,SDL_ttf để tạo hình ảnh, âm thanh.
- Sử dụng pair,file,string.

6.Tài liệu tham khảo
- SDL: https://lazyfoo.net/tutorials/SDL/
- Thuật toán: tham khảo trên The Coding Train.
 
