# projectGTAI-demo-code
## Demo code and setup tutorial
Đây là github repository của nhóm để lưu trữ source code và hướng dẫn setup để sử dụng model multimodal-learning-hands-on-tutorial.
## Hướng dẫn setup để sử dụng demo code
1. Clone repo này về working directory của bạn `git clone https://github.com/24122039Kien/projectGTAI-demo-code.git` hoặc sử dụng VSCODE để clone repo về máy.
2. Tải về các thư viện cần thiết bằng terminal `pip install -r requirements.txt`
3. Chạy quá trình training và prediction, chạy `python multimodal_training.py` nếu bạn muốn tự train bằng dataset của bạn, để làm điểu đó hãy điểu chỉnh `args` dictionary ở trong `main` function
4. Chạy model bằng cách chạy `python multimodal_testing.py` bằng dataset đã có sẵn trong repo này
**Disclaimer** 
Tất cả source code trong github này được viết bởi `dsaaidgovsg` trong  [ github repository của họ](https://github.com/dsaidgovsg/multimodal-learning-hands-on-tutorial.git) và còn sử dụng source file trong [ALBEF's GitHub repo](https://github.com/salesforce/ALBEF)
(nhấn vào filename để mở repository).
## Dataset được sử dụng trong source code này
Dataset được sử dụng là [WebVision](https://data.vision.ee.ethz.ch/cvl/webvision/dataset2017.html) dataset. Trong repo này tôi đã sử dụng dataset được tải sẵn từ google drive trong `prepare_folders_and_dowload_file.sh` của [dsaidgovsg github repository](https://github.com/dsaidgovsg/)
