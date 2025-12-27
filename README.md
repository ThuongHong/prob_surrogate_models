# Mô hình thay thế xác suất (Probabilistic Surrogate Models)

## Mô tả

Đồ án tập trung vào việc nghiên cứu và báo cáo về **Mô hình thay thế xác suất** (Probabilistic Surrogate Models)

## Cấu trúc thư mục

```
.
├── data/                      # Dữ liệu cho demo
│   └── Admission_Predict.csv
├── notebooks/                 # Jupyter notebooks demo
│   ├── demo.ipynb
│   └── regression.ipynb
├── report/                    # Báo cáo LaTeX
│   ├── main.tex              # File chính
│   ├── content/              # Nội dung các chương
│   ├── img/                  # Hình ảnh
│   ├── ref/                  # Tài liệu tham khảo
│   └── appendix/             # Phụ lục
└── requirements.txt          # Thư viện Python cần thiết
```

## Yêu cầu

### Để biên dịch báo cáo

- LaTeX distribution (TeX Live, MiKTeX, hoặc tương tự)
- Các package LaTeX cần thiết (xem trong `hcmus-report-template.sty`)

### Để chạy notebooks

Cài đặt các thư viện Python:

```bash
pip install -r requirements.txt
```

## Nội dung báo cáo

Báo cáo bao gồm các phần chính:

- Surrogate Models
- Gaussian Distribution
- Gaussian Process
- Prediction
- Gradient-Based Optimization
- Noisy Observations
- Fitting

Ngoài ra, báo cáo còn liệt kê một số nghiên cứu gần đây về Gaussian Process.

Notebook `demo.ipynb` được chuyển từ Julia sang Python. Code gốc có thể được tìm thấy [tại đây](https://github.com/algorithmsbooks/algforopt-notebooks)

## License

Xem [LICENSE](LICENSE).
