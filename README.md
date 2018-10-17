# structure_webApp
webApp开发架子，快速搭建webApp相应的页面。可以直接把这个作为基础的wepApp开发的架子，然后根据不同的项目业务需求加上相应的模块。

## 截屏
![运行页面](https://github.com/saucxs/structure_webApp/screenshot/photo1.png)


## 项目运行
   
   ```   
   git clone https://github.com/saucxs/structure_webApp.git
   
   cd structure_webApp
   
   npm install
   
   npm run dev（本地运行 访问：http://localhost:8088）
   
   npm run build （部署上线 生成的dist文件夹放到服务器中即可：需要配置代理，如使用nginx，可参考下面问题中的配置）
   
   ```
   
## 说明
#### 1、跳转页面后active标记
```
最开始使用url.indexOf来处理，后来直接发现vue-router的exact属性更好用。
```
