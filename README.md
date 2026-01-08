# 当代数据管理系统教材 (Contemporary Data Management System Textbook)

本教材内容来源于 GitHub 仓库：[https://github.com/xuanzhouhub/CDMS](https://github.com/xuanzhouhub/CDMS)

## 关于本教材

这是一本关于当代数据管理系统的在线教材，涵盖了现代数据管理系统的核心概念、原理和实践。

## 在线阅读

访问在线阅读地址：[https://frank-whw.github.io/CDMS/](https://frank-whw.github.io/CDMS/)

## 本地运行

本教材使用 [Zensical](https://github.com/zensical/zensical)（基于 MkDocs）构建。如果你想在本地运行查看：

1.  **克隆仓库**：
    ```bash
    git clone https://github.com/frank-whw/CDMS.git
    cd CDMS
    ```

2.  **创建并激活虚拟环境（推荐）**：
    *   Windows:
        ```powershell
        python -m venv .venv
        .venv\Scripts\activate
        ```
    *   macOS/Linux:
        ```bash
        python -m venv .venv
        source .venv/bin/activate
        ```

3.  **安装依赖**：
    ```bash
    pip install -r requirements.txt
    ```

4.  **启动本地服务器**：
    ```bash
    zensical serve
    ```
    然后在浏览器中访问 `http://127.0.0.1:8000`。

## 目录结构

*   `docs/`: 文档源文件
    *   `assets/`: 图片资源
    *   `part1/` - `part5/`: 各章节内容
*   `site/`: 构建后的静态网站（由 `zensical build` 生成，不需要提交）
*   `zensical.toml`: 配置文件

## 原始仓库信息

- **仓库地址**: https://github.com/xuanzhouhub/CDMS
- **仓库名称**: CDMS - Online Textbook of Contemporary Data Management System
- **描述**: 当代数据管理系统在线教材

## 版权声明

本教材的所有内容版权归原始作者所有。请遵守相关的版权协议和使用条款。
