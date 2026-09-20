# 四则运算计算器

一个用于练习 Python 函数和 pytest 测试的小项目。

## 功能

- `add(a, b)`：加法
- `subtract(a, b)`：减法
- `multiply(a, b)`：乘法
- `divide(a, b)`：除法；除数为 0 时抛出 `ValueError`

## 文件

- `calculator.py`：计算器实现
- `test_calculator.py`：pytest 测试
- `requirements-dev.txt`：测试依赖

## 运行测试

```bash
python -m pip install -r requirements-dev.txt
python -m pytest
```
