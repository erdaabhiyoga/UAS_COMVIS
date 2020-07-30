# UAS_COMVIS
untuk menjalankan file ini bisa mengikuti langkah dibawah ini terlebih dahulu
1. install nvcuda
2. install cudnn kemudian pindah folder ke directory C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.0
3. install cudart101.dll(jika di perlukan) kemudian pindah ke directory C:\Users\HP\AppData\Local\Programs\Python\Python37\Lib\site-packages\torch\lib

1. install yolo.weight di https://pjreddie.com/darknet/yolo/
2. buat folder bin kemudian masukan file yolo.weights yg td di install
3. kemudian run di cmd di folder ini dengan command: python setup.py build_ext --inplace
