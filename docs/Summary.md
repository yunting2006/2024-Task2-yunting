# 任务总结

## 使用的 Git 和 Conda 命令
- `git clone`：克隆远程仓库。
- `git checkout -b`：创建并切换分支。
- `git merge`：合并分支。
- `conda create --name task2_env python=3.9`：创建虚拟环境。
- `conda install`：安装依赖。
- `conda env export > environment.yml`：导出环境配置。

## Anaconda 环境配置的优点与难点
- **优点**：隔离项目依赖，避免冲突；便于环境复现。
- **难点**：初次配置需要手动安装依赖，可能遇到版本兼容问题。

## Git 分支管理的经验
- 分支管理清晰了开发流程，主分支保持稳定，功能分支便于实验新特性。

## 部署过程中的问题及解决方案
- **问题**：`Plot.py` 未自动保存图像。
- **解决**：修改代码添加 `plt.savefig()`。
