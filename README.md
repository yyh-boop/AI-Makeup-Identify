当前代码位于目录1下，主要包含：
| 内容 | 说明 |
|------|------|
| `1/train.py`、`1/train.sh` | 训练检测模型 |
| `1/test.py`、`1/demo.py` | 测试与推理 |
| `1/guided-diffusion/` | DIRE 与扩散相关代码 |
| `1/networks/`、`1/utils/` | 网络与工具 |
| `1/wechat_api_server.py` | 后端 HTTP 接口（供小程序等调用） |
| `1/miniprogram/` | 微信小程序前端 |

环境
- Python 3.9（建议）
- 安装 PyTorch（按本机 CUDA 选择版本）后执行：`pip install -r 1/requirements.txt`
数据集与预训练权重体积较大，**默认不包含在仓库中**；下载与目录组织方式见 `1/README.md` 内原文说明。

微信小程序
本地启动服务、配置接口与开发者工具，详见 **`1/README_MINIPROGRAM.md`**。

引用
若使用原论文方法，请引用官方仓库与论文（见 `1/README.md` 文末 Citation）。
