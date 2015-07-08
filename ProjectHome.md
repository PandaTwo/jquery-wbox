jQuery插件<strong>wBox </strong>1.0正式发布——经过一系列的wBox需求分析，进行了wBox的代码重构，去除了一些鸡肋的功能~根据公司项目的需要进行了功能的调整，并且在界面上进行了美化处理~
<p><a href='http://js8.in/wbox/'>查看wBox代码实例</a></p>

<h3>wBox新功能及其变化</h3>
<ol>
<blockquote><li> 优化代码~</li>
<li> 美化界面~</li>
<li>默认可拖动，drag为false关闭</li>
<li> 新增<strong>wBox</strong>关闭方法：wBox.close()</li>
<li> 新增wBox打开方法：wBox.showBox()</li>
<li> 新增wBox定时关闭设置：通过参数timeout设置定时关闭时间</li>
<li> 新增在不触发click事件的前提，显示wBox，$(s).wBox({show:true})</li>
<li>去除灯箱功能（准备做一个单独的jQuery灯箱插件）</li>
<li>去除设置窗口位置</li>
</ol>
<h3>wBox功能特点</h3>
<ol>
<li>背景透明度可以根据实际情况进行调节</li>
<li>可以根据需要添加wBox标题</li>
<li>支持callback函数</li>
<li>支持html内容自定义</li>
<li>支持在wBox显示#ID的内容</li>
<li>支持Ajax页面内容</li>
<li>支持iframe</li>
<li>支持wBox拖拽功能</li>
<li>ESC键，或者在背景上双击即可关闭wBox</li>
<li>Class为wBox_close点击可以关闭wBox，无论是组装的html，还是隐藏的html，甚至于iframe的内容中的.wBox_close</li>
</ol>
<p><a href='http://js8.in/wbox/'>查看wBox代码实例</a></p>