# Mineways Gate · 云控标记

AshenFlame Foundry（MinewaysMobile）的启动闸门读本仓库**根目录的文件数量**：

| 根目录文件数 | 结果 |
|---|---|
| 1 个（只有本 README） | 放行 —— 正常进入 App |
| 2 个及以上 | 拦截 —— 显示「服务已停止」，不可进入 |

## 怎么用

- 停服：往根目录再放**任意一个文件**（例如 `block.txt`），所有设备下次启动即被拦下。
- 恢复：把那个文件删掉，只留 README，设备重启 App 即恢复放行。

## App 侧怎么读

- 地址：`https://api.github.com/repos/151shi23/Mineways-Gate/contents/`
- 只数**根目录**的文件；子目录里的文件不参与计数。
- 网络取不到时按**上次成功的结果**执行；从没取到过则放行（不会因为断网把人锁死）。
