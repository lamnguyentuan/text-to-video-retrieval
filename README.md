# CLIP Video Retrieval

Bộ khung dự án truy xuất video bằng văn bản với CLIP trên dữ liệu MSR-VTT.

## Cấu trúc

- `configs/`: cấu hình các bước xử lý.
- `data/`: video gốc, dữ liệu đã xử lý, caption và embeddings.
- `schemas/`: schema và metadata mẫu.
- `src/`: các mô-đun xử lý dữ liệu, mã hóa, chọn frame, caption, retrieval, reranking, localization và đánh giá.
- `scripts/`: các điểm chạy từng bước của pipeline.
- `notebooks/`: khám phá dữ liệu và thử nghiệm.
- `experiments/`: baseline, ablation và kết quả.
- `tests/`: vị trí dành cho kiểm thử.
- `demo/`: ứng dụng demo.
- `docs/`: kiến trúc, phương pháp và kế hoạch thực nghiệm.

## Trạng thái

Dự án hiện là bộ khung; mã nguồn, cấu hình và kiểm thử cần được triển khai tiếp. Chưa khai báo thư viện phụ thuộc.
