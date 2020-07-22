## 补丁说明：

1.show_systembar_for_pie.zip  --------------------显示mid 状态栏及导航栏功能补丁（已添加自动隐藏导航栏按钮，电源功能按钮，截图按钮等额外功能）；

2.force_optee_use_security_partition.patch ------------默认optee使用security分区，解决客户一些使用拆机料flash（rbmp被写过）导致optee无法完成初始化无法正常开机问题，客户按需打上；

3.fix-focus-error-for-danbeimarket_apk.patch  --------规避处理当贝市场等特殊应用由于自身弹框绘制问题在9.0上导致概率无法操作焦点异常，如应用后续自身新版本解决则不需要使用；

4.modify_PublicVolume(udisk)_can_write_forapp_default.patch  ----------由于安全考虑，9.0默认系统不允许对usb插入的存储设备有写的权限，该补丁可以规避此影响，默认允许对u盘等设备具有写权限，不考虑过google认证的客户可以使用；

5.default_set_uimode_to_mid.patch------默认配置系统uimode为mid模式补丁，建议使用动态uimode功能配置。

6.rk-android9.0-root补丁（rootservice方式）.rar -------SupportSu方式的root补丁包，默认系统已集成，可参考补丁包确认。