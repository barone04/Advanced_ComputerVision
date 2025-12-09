# Advanced ComputerVision: Thị Giác Máy Tính Nâng Cao 

Kho lưu trữ này chứa tất cả các bài tập, thực hành (Lab) và mã nguồn liên quan đến môn học **Thị Giác Máy Tính Nâng Cao (Advanced Computer Vision)** trong chương trình học **2025-2026**.

---

## I. Giới Thiệu

Môn học **Thị Giác Máy Tính Nâng Cao** tập trung vào các chủ đề và thuật toán hiện đại trong lĩnh vực Thị Giác Máy Tính, đặc biệt là ứng dụng của **Học Sâu (Deep Learning)**. 

Các chủ đề chính được đề cập bao gồm:
* **Mô hình Generative (GANs):** Các mạng đối nghịch tạo sinh như DCGAN, CycleGAN, Pix2Pix.
* **Ước lượng Độ Sâu (Depth Estimation):** Kỹ thuật đơn nhãn (Monocular) và đa nhãn (Stereo) để xác định thông tin độ sâu từ hình ảnh.
* **Xử lý Hình ảnh (Image Processing):** Các kỹ thuật tiền xử lý và tăng cường cơ bản.
* **Phát hiện và Theo dõi Vật thể (Object Detection & Tracking):** Nhận dạng vị trí và theo dõi vật thể trong chuỗi hình ảnh/video.
* **Phân đoạn Hình ảnh (Image Segmentation):** Phân loại từng pixel thành các lớp khác nhau (Semantic/Instance Segmentation).
* **Chú thích Hình ảnh với Cơ chế Tập trung (Image Captioning With Attention):** Tạo mô tả văn bản cho hình ảnh bằng cách sử dụng cơ chế chú ý.
* **Phân loại Video (Video Classification):** Phân loại nội dung của chuỗi video.
* **Học Chuyển giao (Transfer Learning):** Tận dụng các mô hình đã được huấn luyện trước.

---

## II. Cấu Trúc Dự Án

Kho lưu trữ được tổ chức theo từng chủ đề lớn của môn học, giúp dễ dàng tìm kiếm và tham khảo mã nguồn cho từng bài Lab/bài tập.

| Thư mục | Mô tả |
| :--- | :--- |
| `Depth_Estimation` | Các bài tập liên quan đến ước lượng độ sâu (Monocular, Stereo). |
| `GAN - Generative Adversarial Networks` | Mã nguồn và Lab về các mô hình GAN (CycleGAN, DCGAN, Pix2Pix). |
| `GraphBase` | Có thể chứa các kiến trúc liên quan đến Graph Neural Networks (GNNs) hoặc cơ sở dữ liệu đồ thị. |
| `ImageCaptioning_With_Attention` | Các mô hình tạo chú thích hình ảnh có sử dụng cơ chế Attention. |
| `Image_Processing` | Các bài tập cơ bản về xử lý hình ảnh. |
| `Object_Detection` | Các dự án và thuật toán phát hiện vật thể. |
| `Object_Segmentation` | Các dự án và thuật toán phân đoạn hình ảnh (Segmentation). |
| `Object_Tracking` | Các dự án về theo dõi vật thể. |
| `Transfer_Learning` | Ví dụ về việc áp dụng kỹ thuật học chuyển giao. |
| `Video_Classification` | Các dự án về phân loại nội dung video. |
| `requirements.txt` | Danh sách các thư viện Python cần thiết cho dự án. |

---

## III. Cài Đặt

Để chạy mã nguồn trong kho lưu trữ này, bạn cần cài đặt các thư viện Python cần thiết.

### 1. Yêu cầu Hệ thống

* **Python:** Phiên bản 3.x (Khuyến nghị 3.8+)
* **Cuda/CuDNN:** Cần thiết nếu bạn muốn tận dụng GPU cho việc huấn luyện.
* **IDE/Môi trường:** PyCharm hoặc Jupyter Notebook (vì các tệp chính là `.ipynb`).

### 2. Cài đặt Môi trường

Sử dụng tệp `requirements.txt` để cài đặt các thư viện cần thiết:

```bash
# Tạo môi trường ảo (Khuyến nghị)
python -m venv venv
source venv/bin/activate  # Trên Linux/macOS
# .env\Scriptsctivate # Trên Windows

# Cài đặt các thư viện
pip install -r requirements.txt 
````

-----

## IV. Hướng Dẫn Chạy

Hầu hết các bài tập và Lab được trình bày dưới dạng **Jupyter Notebook** (`.ipynb`).

1.  **Kích hoạt môi trường ảo** (nếu chưa kích hoạt).
2.  **Khởi động Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
3.  **Tru cập vào các thư mục** và mở các tệp `.ipynb` (ví dụ: `Lab12_cyclegan-toy_PhanDinhThaiBao_22001547.ipynb` trong thư mục `GAN - Generative Adversarial Networks`).
4.  **Chạy từng ô (cell)** trong notebook theo hướng dẫn.
5.  **Lưu ý:** Một số tệp có thể yêu cầu tải xuống bộ dữ liệu (dataset) riêng biệt, bạn cần kiểm tra phần đầu của notebook để biết thêm chi tiết.

-----

## V. Tài Liệu Tham Khảo

Đây là danh sách các tài liệu, sách, khóa học và công cụ đã được sử dụng hoặc tham khảo trong quá trình học tập và hoàn thành các bài tập.

### 1\. Sách

  * Tài liệu 1: [https://drive.google.com/file/d/1xM4d4VqwOr4GdHdbte5kQoGRDvwGvIyJ/view](https://drive.google.com/file/d/1xM4d4VqwOr4GdHdbte5kQoGRDvwGvIyJ/view)
  * Tài liệu 2: [https://drive.google.com/file/d/1lQ1Ig-zHDis7C8hWqEVsbQLp1mBQZ3qJ/view](https://drive.google.com/file/d/1lQ1Ig-zHDis7C8hWqEVsbQLp1mBQZ3qJ/view)
  * Tài liệu 3: [https://drive.google.com/file/d/1lwvWZjErY6b6c3ARDTf1NOimdCZ9d0sT/view](https://drive.google.com/file/d/1lwvWZjErY6b6c3ARDTf1NOimdCZ9d0sT/view)

### 2\. Khóa học

  * **CS231n: Convolutional Neural Networks for Visual Recognition** (Stanford University).

### 3\. Bài báo

  * **Generative Adversarial Networks (GANs)** (Ian Goodfellow et al., 2014)
  * **Image-to-Image Translation with Conditional Adversarial Networks (Pix2Pix)** (Isola et al., 2017)
  * **Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks (CycleGAN)** (Zhu et al., 2017)

### 4\. Công cụ & Framework

  * **PyTorch:** Framework chính được sử dụng để xây dựng và huấn luyện mô hình.
  * **TensorFlow/Keras:** (Nếu có)
  * **OpenCV:** Thư viện cho các tác vụ Thị Giác Máy Tính truyền thống.
  * **Pillow/PIL:** Thư viện xử lý hình ảnh.
-----

## VII. Tác Giả

  * **Tên:** Phan Đình Thái Bảo
  * **MSV:** 22001547

-----

## VIII. Đóng Góp

Mọi đóng góp nhằm cải thiện mã nguồn, tối ưu hóa hiệu suất, hoặc chỉnh sửa lỗi là rất được hoan nghênh. Vui lòng tạo một **Pull Request** hoặc mở **Issue** trên kho lưu trữ này.

-----

** Kho lưu trữ này phục vụ mục đích giáo dục và nghiên cứu.
