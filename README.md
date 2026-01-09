# ⚡ 控制环路参数计算器

## 功能

- Buck 双环控制参数计算
- Boost 双环控制参数计算
- 单相离网逆变 dq 双环控制参数计算
- 单相离网逆变瞬时值双环控制参数计算
- 单相并网逆变电流环控制参数计算

## 安装依赖

```bash
pip install streamlit==1.31.0
pip install numpy==1.26.3
```

## 文件说明

| 文件 | 说明 |
|------|------|
| `app.py` | Streamlit 前端界面 |
| `calculator.py` | 后端计算逻辑 |

## 运行

```bash
streamlit run app.py
```

启动后访问 `http://localhost:8501`
