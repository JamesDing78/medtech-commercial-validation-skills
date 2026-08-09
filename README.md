# Medtech Commercial Validation Skills

一组用于医疗科技、康复、运动健康、教育健康和具身智能产品线的 Codex Skills。

这套 Skills 的核心顺序是：

> 客户价值 -> 真实证据 -> 交易结构 -> 交付负担 -> 合规与风险 -> 公司盈利 -> 继续、调整、暂停或停止

它适合把一个产品想法转化为可验证的客户方案、付费试点、销售计划、财务模型和决策交付包。它不能替代客户访谈、医院医保办确认、注册/法律意见、临床研究或正式合同。

适用对象：医疗器械与康复设备团队、康复机构、运动健康连锁、体育科研团队、学校健康项目、AI/机器人产品团队和医疗科技咨询服务商。

## 60 秒开始

1. 复制 `skills/` 到你的 Skill 目录。
2. 先调用 `$customer-evidence-medtech-commercial-validation`。
3. 输入产品、目标客户、场景、预期用途和现有证据。
4. 再按需要调用医院准入、法规、临床证据、售后或定价专项 Skill。
5. 要求输出客户 ROI、付费试点闸门和 Continue/Adjust/Pause/Stop 决策。

```text
$customer-evidence-medtech-commercial-validation

请评估这个产品是否值得在90天内做付费试点。先分析客户如何获益，
再分析交易结构、合规风险、交付成本和公司盈利。区分事实、假设、
客户确认和待验证信息，不要把市场规模当作客户需求。
```

## Skills

### 总控 Skill

- `customer-evidence-medtech-commercial-validation`：客户证据驱动的医疗科技商业验证总控入口。

### 专项 Skills

- `market-pain-mining`：市场调研与痛点挖掘
- `data-moat-pricing`：多模态数据集、设备、软件和服务定价
- `medical-to-robotics-business-model`：医工交叉三阶段商业模式
- `sim-to-real-feasibility`：仿真到真实和场景落地可行性
- `global-medtech-regulatory-classification`：FDA、NMPA、EU MDR 分类与注册路径
- `clinical-evidence-maude-mining`：临床证据、召回和 MAUDE 风险信号
- `hospital-access-pricing-reimbursement`：医院准入、医保、DRG/DIP 和采购
- `after-sales-service-system`：售后、SLA、校准、备件和服务收入
- `record-replay-sales-review`：销售、演示和售后 Record & Replay 复盘
- `solo-founder-team-building`：单人启动、外部专家和阶段性招聘
- `interactive-pitch-deck`：互动路演和决策 Sites

## 使用方式

将 `skills/` 目录复制到你的 Skill 目录，然后显式调用：

```text
$customer-evidence-medtech-commercial-validation
```

推荐先调用总控 Skill，再根据需要调用专项 Skill。总控 Skill 会要求区分事实、公开证据、客户确认、推断、假设和缺失信息。

## 推荐工作流

1. 明确决策、客户、场景、预期用途和成功标准。
2. 按医疗、科研/体育高校、学校、社区/连锁和 To C 分开建模。
3. 记录客户痛点、现有替代方案、买方、付款方、预算和不购买原因。
4. 建立来源账本，记录观察年份、发布时间、访问日期、可比性和证据等级。
5. 用客户侧 ROI 先验证回本，再建立公司收入和利润模型。
6. 通过访谈、演示、正式报价和付费试点验证，而不是把市场规模当成需求。
7. 应用注册、宣传、医保、隐私、未成年人、临床安全、售后和现金流闸门。
8. 输出 Continue、Adjust、Pause 或 Stop，并列出下一项最小验证动作。

## Agent 角色绑定

公开仓库不包含任何个人 Agent 配置。可以参考 [`agents/README.md`](agents/README.md) 将总控 Skill 分别绑定给 CEO、码农和审核员。

## 商业化

本仓库采用“免费开源核心 + 付费专业服务/企业版”的方式。GitHub 上的 Skill 用于获客和建立信任，收费内容包括行业模板包、商业验证 Sprint、企业私有部署、培训、年度更新和持续支持。详细方案见 [`MONETIZATION.md`](MONETIZATION.md)。

不要在没有付费客户、重复交付证据和续费信号前，直接开发复杂 SaaS 或 GitHub App。

公开包中的 [`commercialization/`](commercialization/) 目录包含产品目录、客户需求表、付费试点模板、交付 SOP 和指标定义。

## 参与和推广

- 提交真实但已脱敏的使用反馈、模板改进和边界案例。
- 在 Discussions 中提出问题或分享使用结果，不要上传患者、学生、客户或内部合同数据。
- 发布版本见 [Releases](https://github.com/JamesDing78/medtech-commercial-validation-skills/releases)。
- 商业合作应基于客户问题、交付范围和验证结果，不以 Star、下载量或市场规模代替需求证据。

## 公开范围与限制

- 本仓库只包含通用方法、模板和工作流，不包含任何特定公司的内部价格、客户名单、设备存量、合同、财务模型或个人信息。
- 公开价格、法规和临床数据使用时必须重新核验有效性、地域和更新时间。
- 医疗器械分类、医保支付、数据交易和疗效宣传均需要结合具体产品和当地规则确认。
- 原始医疗健康数据、未成年人数据、生物识别数据和患者数据不能因为进入项目就自动成为可交易资产或利润。

## 许可证

本项目采用 MIT License。第三方来源、商标、法规文本和数据集仍受其各自权利人约束。
