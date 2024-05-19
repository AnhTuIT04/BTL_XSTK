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

### Chạy dự án trên Kaggle (Khuyên dùng)
- Bạn giữ lại biến ```INPUT_PATH``` trong ```## Kaggle path``` và comment biến ```INPUT_PATH``` trong ```## Local path``` sau đó lưu file lại.
- Truy cập vào Datasets của dự án trên Kaggle ```https://www.kaggle.com/datasets/iliassekkaf/computerparts?resource=downlo``` sau đó đăng nhập vào tài khoản của bạn.
- Tạo 1 ```Notebook``` mới bằng cách bấm vào nút: ```New Notebook```.
- Vào ```File -> Import Notebook``` sau đó tải lên file ```btl-xstk-hk232-l10-n1.ipynb```.
- Chọn ```Run All``` để chạy tất cả cell hoặc chọn ```Run Cell``` trước cell bạn cần chạy.

### Chạy dự án ở local (VS code)

#### Cài đặt và cấu hình
- Để chạy dự án, bạn cần phải cài ```R``` trên máy trước. Link tải ```https://cran.r-project.org/```.
- Cài ```jupyter``` bằng ```pip``` (nếu chưa có):
```
pip install jupyter
```
- Thêm ```jupyter``` vào biến môi trường của máy (đường dẫn tới file ```jupyter.exe```), thường thì đường dẫn sẽ là:
```
C:\Users\ADMIN\AppData\Roaming\Python\Python312\Scripts
```
- Cài ```IRkernel``` bằng ```R``` (nếu chưa có). Mở file ```R.exe```, thường thì đường dẫn sẽ là:
```
C:\Program Files\R\R-4.4.0\bin
```
sau đó cài ```IRkernel``` bằng lệnh:
```
install.packages("IRkernel")
```
thêm kernel R cho Jupyter:
```
IRkernel::installspec()
```
- Cài bộ extensions ```Jupyter``` để chạy file ```jupyter``` trong VS Code (```Jupyter```, ```Jupyter Cell Tag```, ```Jupyter Keymap```, ...)
- Mở file ```btl-xstk-hk232-l10-n1.ipynb``` trong VS Code. Nếu ở góc trên bên phải có hiện kí hiệu R thì VS Code đã tự detect được R kernel. Nếu chưa detect được R kernel thì bấm vào nút ```Select a Kernel``` -> ```Jupyter Kernel ...``` và chọn R kernel.

#### Chạy dự án
- Bạn giữ lại biến ```INPUT_PATH``` trong ```## Local path``` và comment biến ```INPUT_PATH``` trong ```## Kaggle path``` (mặc định là vậy).
- Chọn ```Run All``` để chạy tất cả cell hoặc chọn ```Run Cell``` trước cell bạn cần chạy.
