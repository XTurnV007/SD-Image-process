# 辣椒炒肉图片裁剪器（lajiaochaorou）

#### 介绍
辣椒炒肉图片裁剪器是一个灵活且易于使用的批量图片调整工具。它可以将您的图片调整为任意指定尺寸，并在必要时按比例裁剪。它是一个在线工具，您无需下载或安装到电脑上。辣椒炒肉图片裁剪器完全免费使用。

# -> [演示站点Vercel](https://lajiaochaorou-nine.vercel.app/) <-
# -> [演示站点Github](https://xturnv007.github.io/lajiaochaorou/) <-

# 用于Stable Diffusion的图像裁切工具
在训练Stable Diffusion（或其他生成图像模型）时，我们需要高质量且裁剪为512x512的训练图像。辣椒炒肉图片打标器是快速完成此任务的最佳工具，并且借助[smartcrop.js](https://github.com/jwagner/smartcrop.js/)，它成为了一个非常强大的批量裁剪图像工具。

## 本地安装
克隆此仓库并在您喜欢的浏览器中打开index.html。可以将其添加为书签！
```bash
git clone https://gitee.com/cursorai/lajiaochaorou.git
cd lajiaochaorou
python -m webbrowser index.html  # 或直接打开index.html文件
```

## 使用Docker-Compose运行
```bash
git clone https://gitee.com/cursorai/lajiaochaorou.git
cd lajiaochaorou
docker-compose up -d
# 在浏览器中打开 => http://<HOST_IP>:8080
```

## 作者
- 二次开发作者，支持他们：
  <div style="display: flex; align-items: center; gap: 20px;">
    <div>
      <img src="https://raw.githubusercontent.com/XTurnV007/lajiaochaorou/master/tip/IMG_weixin.JPG" alt="微信收款码" width="300">
      <p style="text-align: center;">赏个鸡腿</p>
    </div>
    <div>
      <img src="https://raw.githubusercontent.com/XTurnV007/lajiaochaorou/master/tip/IMG_zhifubao.JPG" alt="支付宝收款码" width="300">
      <p style="text-align: center;">请杯奶茶</p>
    </div>
  </div>
- [Birme作者，支持他们](https://www.birme.net/)
- 图片单独编辑功能由我编写

## 额外信息
Hermite质量选项使用了[Hermite resize库](https://github.com/viliusle/Hermite-resize)，因此您可以根据源图像尝试获得最佳图像质量。

声明：本项目基于开源项目 [Birme Variant for Stable Diffusion](https://github.com/livelifebythecode/birme-sd-variant) 修改而来，新增了为每张图片单独设置分辨率的功能，也将英文文本翻译成中文，更加适应国内环境。
