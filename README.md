# pix_watercolor
GAN

# spide_pix.py

爬取水彩图片，因为项目需要统一风格的水彩图片才能有效学习，所以选择了爬取同一个作者的水彩图片

再因为水彩图片中多为女性，所以另外爬取女性明星的图片

# 图片预处理

利用人脸识别技术进行人脸裁剪

# 图片存放

--dataset

  --pix2watercolor
  
    --testA
  
    --testB
    
    --trainA
    
    --trainB

testA:存放20多张明星图片用于测试

trainA：存放560多张多张明星图片用于测试

testA:存放20多张水彩图片用于测试

trainA：存放560多张多张水彩图片用于测试

# 原水彩图片风格


# 原明星图片风格



# 利用GAN “unpaired image translation”

![image](https://github.com/inesying/pix_watercolor/blob/main/pix2watercolor/pix2watercolor.png)
