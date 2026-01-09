## 控制环路参数计算器

## 功能

- Buck 双环控制参数计算
- Boost 双环控制参数计算
- 单相离网逆变 dq 双环控制参数计算
- 单相离网逆变瞬时值双环控制参数计算
- 单相并网逆变电流环控制参数计算

## 环境配置

- streamlit==1.31.0
- numpy==1.26.3

```bash
pip install -r requirements.txt
```

## 项目结构

```
calculator_mathcad/
├── app.py          # Streamlit 前端界面
├── calculator.py   # 后端计算逻辑
└── README.md
```

## 运行

```bash
streamlit run app.py
```

启动后访问：
- 本地地址：`http://localhost:8501`
- 局域网地址：`http://192.168.41.107:8501/`
