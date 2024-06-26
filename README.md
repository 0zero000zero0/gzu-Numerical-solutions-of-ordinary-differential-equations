## GZU 数值分析课程设计

该项目是基于 Pyqt6，Python3.12 实现常微分方程数值解的一个小工具
实现了以下算法:

**线性单步法**:

- 前向欧拉法
- 后退欧拉法
- 欧拉法:预测-校正系统
- 梯形法
- 梯形法:预测-校正系统
- Simpson 法(有点问题)

  **线性多步法**:

 
- 四阶 Runge-Kutta 法
- Adams 显式求解公式
- Adams 隐式求解公式
- Adams 法:预测矫正系统
- Milne 法
- Milne 法:预测-矫正系统

支持一阶常微分方程，形式如下:

$$
y' = f(x,y)
$$

## RUN

```bash
pip install -r requirements.txt
python main.py
```
