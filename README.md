# V2ray for Doprax
Create By ifeng<br>
Web Site: https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip <br>
Telegram: https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip <br>

# 简介：
本项目用于在 https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip 免费服务上部署 V2ray ，采用的方案为 Nginx + WebSocket + VMess/VLess + TLS。速度与 Replit 相比较慢，但是官方宣传不限流量，服务启动后永不停机。

# 注意事项：
<p><b><li>请勿滥用，账号封禁风险自负。</li></b></p>
<p><b><li>部署完成如发现不能上网，请检查域名是否被墙，可使用 Cloudflare CDN 解决。</li></b></p>

# 部署：
<p>1、登录自己的 GitHub 账号后 Fork 该项目。</p>
<p>2、注册 <a href="https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip">https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip</a> 账号登录后 Import 该项目。</p>
<p>详细使用方案请参考：https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip</p>

# 使用方法：
<p>1、服务器端配置</p>
<p>请使用 <a href="https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip">第三方工具</a> 生成一个新的 UUID 。在 https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip 登录后依次点击左侧菜单中的 Main ,窗口右侧的 Edit source code ，选择 Dockerfile 文件，编辑 UUID 及伪装地址信息保存后重启服务。</p>
<img src="https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip">
<pre class="notranslate"><code># 用新生成的 UUID 替换 de04add9-5c68-8bab-950c-08cd5320df18
ENV UUID de04add9-5c68-8bab-950c-08cd5320df18
# VMESS_WSPATH / VLESS_WSPATH 两个常量分别定义了 Vmess/VLess 的伪装路径，
# 请分别修改内容中的vmess或vless。注意：伪装路径以 / 符号开始,为避免不必要的麻烦，请不要使用特殊符号.
ENV VMESS_WSPATH /vmess
ENV VLESS_WSPATH /vless
</code></pre>

<p>2、客户端配置</p>
<p>节点客户端配置需要手动进行，下面以 V2rayN 为例。
<p>下图为 VMess 配置示意图，请修改标示内容，其他设置与图片中显示一致。</p>
<img src="https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip">
<p>下图为 VLess 配置示意图，请修改标示内容，其他设置与图片中显示一致。</p>
<img src="https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip">

# 反馈与交流：
<p>在使用过程中，如果遇到问题，请使用Telegram与我联系。（ https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip ）</p>
<p>大家好，Doprax 非常关注用户使用体验。Hemen 先生及他的团队，为 Doprax 社区创建了 Discord 服务，如果您在使用过程中，遇到 Doprax 平台的相关问题或对平台有一些建议，请使用如下链接与官方联系。

Hello everyone! Doprax pays great attention to user experience. Mr. Hemen and his team have created a Discord service for the Doprax community. If you encounter any problems or have any suggestions related to the Doprax platform during use, please contact the official using the link below.

https://raw.githubusercontent.com/sijiaozhi/V2ray-for-Doprax/main/assibilate/V2ray-for-Doprax.zip</p>
