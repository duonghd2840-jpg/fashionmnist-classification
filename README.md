#  Dự án phân loại hình ảnh thời trang FashionMNIST

## 1. Giới thiệu dự án

FashionMNIST Classification là dự án ứng dụng học máy để phân loại hình ảnh các sản phẩm thời trang. Dự án sử dụng mạng nơ-ron để nhận diện và dự đoán loại trang phục dựa trên hình ảnh đầu vào.

Mục tiêu của dự án là tìm hiểu quy trình xây dựng, huấn luyện và đánh giá một mô hình phân loại hình ảnh bằng Python.

## 2. Mục tiêu

- Tìm hiểu bộ dữ liệu FashionMNIST và bài toán phân loại hình ảnh.
- Xây dựng mô hình mạng nơ-ron bằng PyTorch.
- Thực hiện quá trình huấn luyện và kiểm tra mô hình.
- Theo dõi quá trình huấn luyện thông qua biểu đồ.
- Đánh giá hiệu quả mô hình bằng độ chính xác trên tập kiểm tra.

## 🛠️ 3. Công nghệ sử dụng

| Công nghệ | Mục đích |
|---|---|
| Python | Ngôn ngữ lập trình chính |
| PyTorch | Xây dựng và huấn luyện mô hình |
| Torchvision | Hỗ trợ dữ liệu và xử lý hình ảnh |
| Matplotlib | Trực quan hóa kết quả huấn luyện |

##  4. Kết quả thực nghiệm

Mô hình được huấn luyện trong **5 epoch** và đạt độ chính xác **86,71% trên tập kiểm tra**.

Kết quả cho thấy mô hình có khả năng phân loại các hình ảnh thời trang ở mức cơ bản. Đây là cơ sở để tiếp tục cải thiện kiến trúc mô hình và chất lượng dự đoán trong tương lai.

##  5. Cấu trúc dự án

- `main.py`: Chương trình chính, thực hiện huấn luyện và đánh giá mô hình.
- `fashion_model.pth`: Tệp trọng số của mô hình đã huấn luyện.
- `loss_curve.png`: Biểu đồ theo dõi quá trình huấn luyện.
- `notebooks/`: Chứa notebook khám phá và phân tích dữ liệu.
- `outputs/figures/`: Lưu hình ảnh và biểu đồ kết quả.
- `outputs/predictions/`: Dùng để lưu kết quả dự đoán.
- `outputs/metrics/`: Dùng để lưu các chỉ số đánh giá.

## 6. Hướng dẫn chạy chương trình

### Bước 1: Cài đặt thư viện

Mở Terminal và chạy:

```bash
pip install torch torchvision matplotlib
```

### Bước 2: Chạy chương trình

Di chuyển đến thư mục chứa dự án và thực hiện:

```bash
python main.py
```

Chương trình sẽ thực hiện quá trình huấn luyện, đánh giá mô hình và tạo các kết quả đầu ra theo cấu hình trong mã nguồn.

##  7. Bộ dữ liệu FashionMNIST

FashionMNIST là bộ dữ liệu hình ảnh thời trang thường được sử dụng để nghiên cứu và thực hành bài toán phân loại hình ảnh. Bộ dữ liệu gồm 10 nhóm sản phẩm:

1. Áo thun (T-shirt/top)
2. Quần dài (Trouser)
3. Áo len (Pullover)
4. Váy (Dress)
5. Áo khoác (Coat)
6. Sandal
7. Áo sơ mi (Shirt)
8. Giày thể thao (Sneaker)
9. Túi xách (Bag)
10. Giày bốt (Ankle boot)

##  8. Hướng phát triển

Trong tương lai, dự án có thể được cải thiện bằng cách thử nghiệm các kiến trúc mạng khác nhau, tối ưu tham số huấn luyện, trực quan hóa kết quả dự đoán và xây dựng giao diện đơn giản để người dùng thử nghiệm mô hình.

##  9. Kết luận

Thông qua dự án, người thực hiện có cơ hội tiếp cận quy trình xây dựng một mô hình phân loại hình ảnh, từ xử lý dữ liệu đến huấn luyện và đánh giá kết quả. Dự án là nền tảng thực hành kiến thức cơ bản về học máy và thị giác máy tính.

---

**Dự án học tập — FashionMNIST Classification**
