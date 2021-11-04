# Đề bài: tính x^11 với số lượng phép nhân ít nhất

## Ý tưởng:
- Nếu nhân như bình thường x.x.x.x.x.. thì ta sẽ cần 10 lần nhân, rõ ràng đây là số lần nhân nhiều nhất để tính x^11.
- Dễ dàng thấy được rằng 11 = 4 + 4 + 2 + 1, 4 = 2 + 2, 2 = 1 + 1.

=> x^11 = x^4 . x^4 . x^2 . x, x^4 = x^2 . x^2, x^2 = x . x sẽ tính được x^11 với 5 lần.

## Lưu đồ:
![bài 1](https://user-images.githubusercontent.com/53053154/139592905-8569452f-4f37-4c97-8c6d-8f389f937f28.png)

## P/s:
- Ngoài ra ta cũng có thể tách thành 11 = 5 + 5 + 1, 5 = 2 + 2 + 1, 2 = 1 + 1 để tính x^11 với 5 lần nhân.
