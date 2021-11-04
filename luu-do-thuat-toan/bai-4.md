# Đề bài: Tính S(x, n) = ![de-bai](https://latex.codecogs.com/gif.latex?-x%5E%7B2%7D&plus;x%5E%7B4%7D-x%5E%7B6%7D&plus;...&plus;%28-1%29%5E%7Bn%7Dx%5E%7B2n%7D)

## Ý tưởng:
- Sử dụng vòng lặp để tính.
- ![](https://latex.codecogs.com/gif.latex?%28-1%29%5E%7Bn%7Dx%5E%7B2n%7D) tương đương với ![image](https://user-images.githubusercontent.com/53053154/139860298-4cb8e1ca-176f-4ecf-981d-b7c0aa403a80.png).

=> Ta chỉ cần tính ![](https://latex.codecogs.com/gif.latex?%28-x%5E2%29%5Ei) ứng với mỗi vòng lặp rồi cộng vào biến "kqua".

## Lưu đồ:
![bài 4](https://user-images.githubusercontent.com/53053154/139860892-bc94dc49-4235-46a9-8d32-432f366f199e.png)

## P/s:
- Thay vì xét xem biến đếm "i" chẵn hay lẻ để cộng trừ vào kết quả, ta có thể nhân ![](https://latex.codecogs.com/gif.latex?-x%5E2) vào biến phụ "temp" ở mỗi vòng lặp để tiết kiệm thời gian chạy.
