Summary Table

Author:	Ngan, Tan Lam

Title:	YOLO v.1 (CNN) Object Detection & classification. 

Topics:	Ứng dụng trong computer vision, sử dụng thuật toán chính là CNN

Descriptions:	Input sẽ là các tấm hình ở sample_img/... và file labels.txt đặt tên nhãn tương ứng của object. Khi train xong sẽ trả ra output sample_img/out/ & json output cùng thư mục lưu nhãn & thôn số tương ứng . Sử dụng trọng số weights đã train để predict bounding box và class của các object trong hình. 
  
Github Link: 

Framework:	Darknet ( based o Darkflow of author={Trieu, Trinh Hoang} )

Dependencies: Python3, tensorflow 1.0, numpy, opencv 3, Cython extensions. 

Configuration: [convolutional]
batch_normalize = 1
size = 1
stride = 1
pad = 1
activation = linear

Pretrained Models:	Sử dụng weight đã được train sẵn https://pjreddie.com/media/files/tiny-yolo.weights

Datasets:	Mô hình được train với bộ dữ liệu coco. Ngoài ra còn có các tập dữ liệu có thể sử dụng: PASCAL VOC, Open Images Dataset, …. 
