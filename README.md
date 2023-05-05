# Mediapipe
#EN
This code is a Python program designed to perform hand detection and hand position analysis using the MediaPipe and OpenCV libraries. The program consists of two different sections:

The first section processes static image files that contain one or more hands. This section reads all image files in a specific folder, performs hand detection, and prints information about hand position.

The second section performs real-time hand detection using a webcam. This section captures the camera image, performs hand detection, prints information about hand position, and displays the results in real-time.

In the second section, it detects whether the hand is open or closed and prints this information on the screen. It looks at the coordinates of certain points on the hand (points 9 and 12) and determines whether the hand is open or closed based on the position of these points relative to each other along the y-axis.


#TR
Bu kod, MediaPipe ve OpenCV kütüphanelerini kullanarak el tespiti ve el pozisyonu analizi yapmak için oluşturulmuş bir Python programıdır. Program iki farklı bölümden oluşmaktadır:

İlk bölüm, bir veya daha fazla elin bulunduğu statik görüntü dosyalarını işlemektedir. Bu bölüm, belirli bir klasördeki tüm görüntü dosyalarını okur, el tespiti yapar ve el pozisyonu hakkında bilgi yazdırır.

İkinci bölüm, webcam kullanarak gerçek zamanlı olarak el tespiti yapar. Bu bölüm, kamera görüntüsünü alır, el tespiti yapar, el pozisyonu hakkında bilgi yazdırır ve sonuçları gerçek zamanlı olarak görüntüler.

İkinci bölümde, elin açık mı yoksa kapalı mı olduğunu tespit eder ve bu durumu ekrana yazdırır. Bunun için elin belirli bir noktasındaki (9. ve 12. noktalar) koordinatlarına bakar ve bu noktaların y diğerine göre konumuna göre elin açık veya kapalı olduğunu belirler.
