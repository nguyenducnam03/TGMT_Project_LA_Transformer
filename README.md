# Person Re-Identification with a Locally Aware Transformer
- Mã nguồn được trích xuất từ: https://github.com/SiddhantKapil/LA-Transformer.git.
# Cách chạy
- Mã nguồn được thực thi trên kaggle, với ACCELERATOR sử dụng GPU T4 x2.
- Ta tải file la-transformer.ipynb lên kaggle, sau đó tải bộ dataset Market 1501 (Có thể tải theo link bên dưới, hoặc trong dataset Kaggle) và tải lên Kaggle.(Chú ý thay đổi link đường dẫn đến dataset trong data_dir cho phù hợp).
## Nếu huấn luyện từ đầu
- Ta có thể chạy hết file để huấn luyện lại từ đầu (Điều chính các tham số như epochs, lr cho phù hợp).
## Nếu chỉ chạy kiểm thử
- Ta tải lên Kaggle bộ huấn luyện sẵn (link bên dưới - và đổi đường dẫn đến bộ trọng số save_path cho phù hợp)
- Sau đó bỏ qua phần train, chạy phần trước đó và phần test (Sử dụng gpu t4x2 kaggle để kích hoạt cuda).
# Result
- Kết quả được hiện thì ở cuối file.
- Hoặc hiển thị 10 ảnh giống nhất.
- Hoặc hiển thị 1 ảnh giống nhất.
# Dataset and pretrained weights
https://drive.google.com/drive/folders/1CRkfn9iLEItaYur1WGf2abvpd2vT7nRB
  
