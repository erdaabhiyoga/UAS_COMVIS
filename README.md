# UAS_COMVIS
untuk menjalankan file ini bisa mengikuti langkah dibawah ini terlebih dahulu
1. install cuda
2. pindah folder cudnn ke directory C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.0
3. install cudart101.dll(jika di perlukan) kemudian pindah ke directory C:\Users\HP\AppData\Local\Programs\Python\Python37\Lib\site-packages\torch\lib
FILE DIATAS BISA DI DOWNLOAD DI DRIVE saya di https://drive.google.com/drive/folders/1MLdPn71piqk2I45W5AbGMlQrHQr7L9QT?usp=sharing

kemudian buka folder projeknya
1. install yolo.weight di https://pjreddie.com/darknet/yolo/
2. buat folder bin kemudian masukan file yolo.weights yg td di install
3. kemudian run di cmd di folder projek ini dengan command: python setup.py build_ext --inplace
4. setelah itu run di cmd python part4_video.py
