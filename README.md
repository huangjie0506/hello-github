基于 webpack4.x 的多页应用脚手架：

css: 采用 scss，并在配置中默认引入 CONST.scss，无需手动引入

 模板: 采用 pug，[layout]文件为公用部分

 static 引入方式: 使用相对路径引入（拷贝不打包）

 assets 图片引入方式: 背景图使用相对路径、img 使用：img(src="${require(`@/assets/s_rate_red_b.png`)}")（打包）
 
UI 路由
