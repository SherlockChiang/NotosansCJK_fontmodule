刷机、刷入 Magisk 模块可能会导致系统无法正常启动，请在操作前审慎考虑，并建议备份重要数据。因操作不当导致的系统故障（包括卡开机动画、功能异常等）或效果异常与模块作者无关。

兼容性调整（仅供参考）

为了使该模块模板更加适合您的手机，需要对模块模板内的配置文件进行调整：

- **OPPO/一加 ColorOS：** 将 `/system/etc/fonts.xml` 复制到 `/system/system_ext/etc/` 目录并重命名为 `fonts_base.xml`。
- **一加 HydrogenOS 11 及以上版本：** 将 `/system/etc/fonts.xml` 复制到相同文件夹，并重命名为 `fonts_base.xml。`
- **魅族 Flyme：** 将 `/system/etc/fonts.xml` 复制 3 份到相同文件夹，并重命名为以下 3 个文件： `fonts_flyme.xml`、`fonts_inter.xml` 和 `fonts_slate.xml`。
- **小米 MIUI 12.5：** 需刷入 [空字体模块](https://pan.nianbroken.top/d/OnedriveShare/%E7%A9%BA%E5%AD%97%E4%BD%93-%E8%87%AA%E5%8A%A8%E8%AF%86%E5%88%ABv4.4.zip)。

如有其他设备的兼容性调整，请在 https://blog.nianbroken.top 的留言板中提出。

字体模块作者：https://www.nianbroken.top/

QQ： 2971802058\

WeChat： NianBroken

Github： NianBroken

Gmail： suinian666@gmail.com

二改作者：酷安@XYHXH46、Uranium92
