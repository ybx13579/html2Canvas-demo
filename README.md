# html2Canvas-demo
> **如有帮助谢谢star**   :star::star::star::star::star: 



 
这是html2Canvas的一个小例子，目前发现的缺点就是不能截视频。
可以通过纯JS对浏览器端经行截屏，但截图的精确度还有待提高，部分css不可识别，所以在canvas中不能完美呈现原画面样式。
 
## 支持的浏览器

- Firefox 3.5+
- Google Chrome
- Opera 12+
- Safari 6+
- IE9+


## 可用参数
<table>
<thead>
<tr>
<th>参数名称</th>
<th>类型</th>
<th>默认值</th>
<th>描述</th>
</tr>
</thead>
<tbody>
<tr>
<td>allowTaint</td>
<td>boolean</td>
<td>false</td>
<td>Whether to allow cross-origin images to taint the canvas---允许跨域</td>
</tr>
<tr>
<td>background</td>
<td>string</td>
<td>#fff</td>
<td>Canvas background color, if none is specified in DOM. Set undefined for transparent---canvas的背景颜色，如果没有设定默认透明</td>
</tr>
<tr>
<td>height</td>
<td>number</td>
<td>null</td>
<td>Define the heigt of the canvas in pixels. If null, renders with full height of the window.---canvas高度设定</td>
</tr>
<tr>
<td>letterRendering</td>
<td>boolean</td>
<td>false</td>
<td>Whether to render each letter seperately. Necessary if letter-spacing is used.---在设置了字间距的时候有用</td>
</tr>
<tr>
<td>logging</td>
<td>boolean</td>
<td>false</td>
<td>Whether to log events in the console.---在console.log()中输出信息</td>
</tr>
<tr>
<td>proxy</td>
<td>string</td>
<td>undefined</td>
<td>Url to the proxy which is to be used for loading cross-origin images. If left empty, cross-origin images won't be loaded.---代理地址</td>
</tr>
<tr>
<td>taintTest</td>
<td>boolean</td>
<td>true</td>
<td>Whether to test each image if it taints the canvas before drawing them---是否在渲染前测试图片</td>
</tr>
<tr>
<td>timeout</td>
<td>number</td>
<td>0</td>
<td>Timeout for loading images, in milliseconds. Setting it to 0 will result in no timeout.---图片加载延迟，默认延迟为0，单位毫秒</td>
</tr>
<tr>
<td>width</td>
<td>number</td>
<td>null</td>
<td>Define the width of the canvas in pixels. If null, renders with full width of the window.---canvas宽度</td>
</tr>
<tr>
<td>useCORS</td>
<td>boolean</td>
<td>false</td>
<td>Whether to attempt to load cross-origin images as CORS served, before reverting back to proxy--这个我也不知道是干嘛的</td>
</tr>
</tbody>
</table>



## 效果图预览： 

<img src="show.jpg">


