# 課題６　画像の二値化　　
ORG=imread('Lenna.png');  
ORG= rgb2gray(ORG);  
imagesc(ORG); colormap(gray); colorbar;  

によって、原画像を白黒濃淡画像へ変換し，結果は図１に示す．　

![原画像](https://github.com/hongyuting2017/image_processing/blob/master/image/kadai6-1.jpg)  
図1 白黒濃淡画像