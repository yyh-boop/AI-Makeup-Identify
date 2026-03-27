当前代码位于目录1下，主要包含：
| 内容 | 说明 |
|------|------|
| `src/train.py`、`src/train.sh` | 训练检测模型 |
| `src/test.py`、`src/demo.py` | 测试与推理 |
| `src/guided-diffusion/` | DIRE 与扩散相关代码 |
| `src/networks/`、`src/utils/` | 网络与工具 |
| `src/wechat_api_server.py` | 后端 HTTP 接口（供小程序等调用） |
| `src/miniprogram/` | 微信小程序前端 |

环境
- Python 3.9（建议）
- 安装 PyTorch（按本机 CUDA 选择版本）后执行：`pip install -r src/requirements.txt`
数据集与预训练权重体积较大，**默认不包含在仓库中**；下载与目录组织方式见 `1/README.md` 内原文说明。

微信小程序
本地启动服务、配置接口与开发者工具，详见 **`src/README_MINIPROGRAM.md`**。

引用
若使用原论文方法，请引用官方仓库与论文（见 `src/README.md` 文末 Citation）。
