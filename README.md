# COSMOGENESIS

**Relational Genesis Physics, Universe-History Engine, and Falsifiable Cosmology Laboratory**  
**关系发生物理、宇宙新史引擎与可反驳宇宙学实验室**

COSMOGENESIS 是一套独立、可运行、可重演的基础物理研究系统。它尝试从“对象之前”的关系发生出发，统一解释量子、规范场、曲率、物质、时空、时间箭头、生命与意识候选，并以透明的合成实验、注册预测和开放失败条件约束理论扩张。

配套专著：**《宇宙的物理新史：从差异发生到生命重写未来》**。

## 1. Project overview

项目将宇宙的最低候选结构写成四类关系：

1. 能够改变后续可能性的差异；
2. 能在局部组合的变换；
3. 不能被无损拼成唯一全局图景的阻碍；
4. 将局部可能固化为历史的记录形成。

系统不宣称已经完成终极理论，而是把一条大胆候选链转化为可执行对象、可复现实验、可撤回预测和明确证据边界。

## 2. Core problem

现代物理拥有极成功的局部理论，但尚无一套得到实验确认的单一框架，能够同时导出：

- 量子理论及测量结果；
- 时空与引力；
- 标准模型的规范群、粒子谱与常数；
- 宇宙初始条件、暗物质和暗能量；
- 时间箭头；
- 生命的开放演化；
- 意识相关的内部因果组织。

COSMOGENESIS 的目标不是以新名词覆盖这些空白，而是逐项记录：假设是什么、机制怎样运行、什么结果会推翻它。

## 3. Key innovations

- **事件优先**：不把粒子和时空预设为最终对象。
- **后果性差异**：差异只有在改变可达未来时才取得物理资格。
- **局部可组合、全局未必闭合**：允许局部理论一致而不存在唯一经典全局截面。
- **联络与 holonomy**：规范场和曲率被理解为局部框架比较及闭路剩余。
- **记录时间箭头**：经典历史由差异的冗余复制与不可逆可访问性形成。
- **约束重写生命**：生命候选不仅维持约束，还能修改维持方式和状态空间。
- **内部后果意识候选**：意识相关组织取决于内部差异是否由同一持续过程承担并改变未来。
- **注册预测**：每项高强度主张都携带反证条件，失败不能被静默改名。

## 4. System architecture

```text
local event contexts
  -> admissible transformations
  -> complex path amplitudes
  -> contextual gluing obstructions
  -> transport and holonomy
  -> redundant records and effective time
  -> stable defects and matter
  -> emergent causal geometry
  -> self-reconstructing constraints
  -> life and consciousness candidates
  -> registered predictions and settlement
```

核心模块位于 `src/cosmogenesis/`：

- `model.py`：事件、输运、记录、约束和实验结果的数据结构；
- `experiments.py`：八类确定性参考实验；
- `predictions.py`：十项注册预测及明确反证；
- `__main__.py`：命令行入口。

## 5. Directory structure

```text
cosmogenesis/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── CITATION.cff
├── SECURITY.md
├── GOVERNANCE.md
├── CONTRIBUTING.md
├── pyproject.toml
├── run_demo.py
├── run_tests.py
├── src/cosmogenesis/
├── tests/
├── schemas/
├── examples/
├── docs/
├── figures/
├── outputs/
└── studio/
```

## 6. Installation

Python 3.10 或更高版本：

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\\Scripts\\activate
python -m pip install --upgrade pip
python -m pip install -e .
```

也可安装发行 Wheel：

```bash
python -m pip install cosmogenesis-1.0.0-py3-none-any.whl
```

## 7. Quick start

```bash
python run_demo.py
python run_tests.py
```

命令行模式：

```bash
python -m cosmogenesis
```

默认结果写入 `outputs/`。

## 8. Command examples

仅运行测试：

```bash
python -m pytest -q
```

从 Python 调用：

```python
from cosmogenesis.experiments import run_all_experiments

result = run_all_experiments("outputs")
print(result["run_hash"])
```

## 9. Input and output formats

输入主要是实验参数和确定性随机种子。输出包括：

- `reference_results.json`：全部实验及注册预测；
- `run_proof.json`：运行哈希与实验数量；
- `registered_predictions.csv`：预测、范围和反证；
- 图像和离线 Studio 数据。

JSON Schema 位于 `schemas/`。

## 10. Configuration

当前参考实现采用代码级显式参数，不隐藏远程配置。关键参数包括：

- 路径数量与相位分布；
- 图节点、连接阈值和潜在维数；
- 记录复制可靠率；
- 世界变换时点、修复率和规则重写幅度；
- 规范耦合初值与一圈 beta 系数；
- 非奇异宇宙学的时间尺度和指数。

修改参数后必须生成新的运行哈希，不得覆盖旧结果。

## 11. Test instructions

```bash
python run_tests.py
```

测试覆盖：

- 确定性重演；
- 情境性全局赋值阻碍；
- 规范 holonomy 不变量；
- 图几何构建；
- 记录恢复；
- 规则重写生命对照；
- 最小标准模型耦合不精确统一；
- 非奇异尺度因子。

## 12. Reproducibility

- 所有随机实验均使用固定种子；
- JSON 使用规范化排序后计算 SHA-256；
- 参考运行的 `run_hash` 可用于逐版本比对；
- 发行包附带文件清单和 SHA-256 校验；
- 不依赖网络服务或商业模型。

## 13. Evidence boundaries

本项目的参考实验是**透明、确定性的合成机制实验**。它们能够证明：

- 所提出的关系可以被程序化；
- 不同机制能够被分离和消融；
- 理论能够产生可结算预测。

它们不能证明：

- 已经发现现实宇宙的最终本体；
- 合成结果等同于实验室或天文观测；
- 生命或意识已经在参考进程中产生；
- 注册预测必然正确。

## 14. Limitations

- 当前情境性实验只是有限组合见证；
- 图几何不构成唯一时空重建定理；
- 一圈耦合运行不足以完成精密大统一；
- 非奇异宇宙学只是运动学候选；
- 生命与意识模块尚未连接真实生物或人工主体数据；
- 终极理论可能需要当前状态空间中不存在的新变量。

## 15. Security and privacy

系统默认离线运行：

- 无网络调用；
- 无 Shell 自主执行接口；
- 无凭据、支付或机器人控制；
- 不采集个人数据；
- 输出仅写入用户指定目录。

漏洞披露流程见 `SECURITY.md`。

## 16. Governance

重大理论或代码变化必须：

1. 保留旧版本和旧运行哈希；
2. 明确新增假设；
3. 提交反证条件；
4. 说明哪些旧结论失效；
5. 接受独立实现和合法分叉。

详见 `GOVERNANCE.md`。

## 17. Contribution guide

欢迎提交：

- 机制反例；
- 独立复现；
- 更严格的数学推导；
- 现实数据适配器；
- 新预测及预注册结算；
- 可访问性和界面改进。

请先阅读 `CONTRIBUTING.md`。

## 18. License

代码以 Apache License 2.0 发布。书稿、图表和研究文本的具体许可见交付包中的版权说明；引用不等于认可全部理论结论。

## 19. Changelog

版本变化见 `CHANGELOG.md`。任何失败预测和撤回结论必须保留在变更历史中。

## 20. Citation

推荐引用格式见 `CITATION.cff`：

```text
COSMOGENESIS: Relational Genesis Physics, Universe-History Engine,
and Falsifiable Cosmology Laboratory, version 1.0.0, 2026.
```

## Final statement

COSMOGENESIS 的核心候选是：

> 宇宙不是由对象首先构成，而是由能够改变未来的差异、局部可组合的变换、不可消除的拼合阻碍和记录形成共同构成。对象、粒子、场、时空、生命与意识，是这一发生过程在不同尺度上的稳定形态。
