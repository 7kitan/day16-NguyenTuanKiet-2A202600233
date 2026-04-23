# Báo Cáo Kết Quả Benchmark

## Thông tin cấu hình
- **Instance:** r5.2xlarge
- **Thời gian tải dữ liệu:** 1.67 giây
- **Thời gian huấn luyện:** 1.13 giây
- **Iteration tốt nhất:** 1

## Đánh giá mô hình
- **AUC ROC:** 0.9382
- **Accuracy:** 99.27%
- **F1 Score:** 0.2925
- **Precision:** 0.1755
- **Recall:** 0.8776

## Hiệu suất suy luận
- **Độ trễ (1 hàng):** 0.16 ms
- **Throughput (1000 hàng):** 3,778,652.25 RPS

## Kết luận
Mô hình đạt hiệu suất cao với AUC ROC 0.9382 và accuracy 99.27%. Tuy nhiên, precision thấp (0.1755) cho thấy có nhiều false positive. Thời gian huấn luyện nhanh (1.13s) và độ trễ suy luận rất thấp (0.16ms), phù hợp cho ứng dụng real-time.