# Báo cáo bài tập lớn môn Xác Suất thống kê
Đây là repository chứa source code R của nhóm.

## Cách clone source code về máy
```
git clone https://github.com/AnhTuIT04/BTL_XSTK.git
cd BTL_XSTK
```
## Cách chạy dự án
Tại mục ```Đọc dữ liệu``` trong file ```btl-xstk-hk232-l10-n1.ipynb```
```
## Local path
INPUT_PATH = "./All_GPUs.csv"
## Kaggle path
# INPUT_PATH = "/kaggle/input/computerparts/All_GPUs.csv"
```
### Chạy dự án ở local (VS code)
- Để chạy dự án, bạn cần phải cài ```R``` trên máy trước.
- Bạn giữ lại biến ```INPUT_PATH``` trong ```## Local path``` và comment biến ```INPUT_PATH``` trong ```## Kaggle path``` (mặc định là vậy).
- Chọn ```Run All``` để chạy tất cả cell hoặc chọn ```Run Cell``` trước cell bạn cần chạy.

### Chạy dự án trên Kaggle
- Bạn giữ lại biến ```INPUT_PATH``` trong ```## Kaggle path``` và comment biến ```INPUT_PATH``` trong ```## Local path``` sau đó lưu file lại.
- Truy cập vào Datasets của dự án trên Kaggle ```https://www.kaggle.com/datasets/iliassekkaf/computerparts?resource=downlo``` sau đó đăng nhập vào tài khoản của bạn.
- Tạo 1 ```Notebook``` mới bằng cách bấm vào nút: ```New Notebook```.
- Vào ```File -> Import Notebook``` sau đó tải lên file ```btl-xstk-hk232-l10-n1.ipynb```.
- Chọn ```Run All``` để chạy tất cả cell hoặc chọn ```Run Cell``` trước cell bạn cần chạy.
