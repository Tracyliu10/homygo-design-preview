# Homygo 五个服务内页设计说明

这份说明与五页可浏览设计稿一起交给设计公司，作为第一版 UI 的制作依据。沿用现有首页的导航层级、明亮居住场景和简洁排版，把服务页面统一为蓝色主调。当前为设计审阅稿，不代表服务政策已经确定。

## 品牌与视觉

- 现有首页 Logo 写作 Homygo 留家；用户此前使用 HomeyGo。正式制作前确认英文拼写。本稿沿用 Logo 的 Homygo，不改动 Logo。
- 主色暂定 #095287，取自现有低分辨率 Logo 的近似蓝色，须用品牌标准色替换或确认。
- 深色文字 #19384D，辅助文字 #637581，浅蓝底 #EDF5FA，边框 #DBE6ED，主体白底。橙色只保留在原 Logo 中，不进入大面积背景或主按钮。
- 首页样式使用 Poppins。本稿使用 Poppins 字体栈，离线时回退到本机无衬线字体；正式项目应加载合法可用的字体文件。
- 桌面内容宽度 1160px，页面左右留白不低于 32px；首屏左右分栏，文字略宽于图片。首屏标题 46px，区块标题 30px，正文 16px，辅助正文 14px。移动端标题 37px，布局改为单栏，输入框正式实施建议使用至少 16px 字号。
- 按钮圆角 8px，卡片圆角 14px，图片圆角 22px；使用克制边框，避免过量阴影。三张服务卡片采用同一视觉系统，正式设计可替换数字标记为统一蓝色线性图标。
- 本稿首屏图片来自保存首页的房源素材，仅用于布局审阅，不是服务实拍。接送机换真实机场接送场景；手机套餐换年轻人自然使用手机场景；其余选真实明亮公寓和服务细节，避免夸张摆拍。

## 所有页面共用结构

1. 首页导航与面包屑，服务项高亮。
2. 首屏：服务名称、简短主标题、一段服务说明、一个咨询按钮、右侧图片。
3. 服务内容：三张卡片。清洁另有可展开清单；能源以电、气、网三项呈现，协助说明放在正文。
4. 浅蓝流程区：三步，分别说明客户提交什么、确认什么、后续如何安排。
5. 申请区：左侧说明和关键条件，右侧短表单。首屏及末尾按钮锚点跳转至本页表单。
6. FAQ：三条可展开问答，默认收起。
7. 蓝底收尾咨询入口。
8. 继承首页页脚、联系信息和品牌内容。页脚公司名称与隐私链接正式实施前核实。

设计稿顶部中文切换条、演示提示属于审阅工具，不能进入正式站。导航中的非服务入口仅展示排版，不代表本稿包含对应页面。演示表单不发送、不保存，也没有接入原测试站。

## 文案优化原则

采用英文面向客户、中文向设计公司说明。把原稿中“Book a Ride”等立即预订的语义改为请求或报价，便于先确认费用和服务可用性。无需支付、未接入实时库存的流程，不使用预约成功或开通成功的提示。不展示未确认的价格、运营商、覆盖城市、等待时长、24 小时响应、退押金保证或虚构评价。

## 每页设计及英文文案

### 接送机

建议路径：/services/airport/

设计重点：右侧首屏暂用首页房源照片表示到家场景；正式替换为真实机场接送照片。表单区分接机和送机，送机增加期望接车时间。

首屏服务名：Airport Pickup & Drop-off

主标题：From the airport. To your front door.

介绍：Plan your arrival or departure with airport transfer support for your journey in Australia.

全页主按钮：Request a Transfer

服务内容标题：A smoother arrival

- **Airport pickup**：Share your flight details and destination so we can help arrange your arrival.
- **Airport drop-off**：Plan a transfer from your address to the airport before you travel.
- **Your travel needs**：Tell us about passengers and luggage so suitable options can be confirmed.

三步流程：

1. **Share your trip**：Send your airport, flight, date, address and passenger details.
2. **Confirm the details**：Review availability, vehicle arrangements and the quoted fee.
3. **Meet your driver**：Receive your meeting instructions once the booking is confirmed.

表单标题：Tell us about your journey

专属字段：Transfer type（Airport pickup / Airport drop-off）；Airport and flight number；Arrival / departure date；Scheduled flight time；Pickup / destination address；Passengers and luggage。

共同字段：姓名、邮箱、电话；联系渠道至少留一种。正式实现应根据渠道选择动态显示字段，避免全部强制填写。

FAQ：

- **What information should I provide?**
  Please share your flight number, airport, travel date and scheduled time, address, passenger count and luggage details.
- **What if my flight changes?**
  Let our team know as soon as possible. Waiting arrangements and any extra fees should be confirmed before booking.
- **Can I bring extra luggage?**
  Tell us the number and size of bags when you enquire. Vehicle suitability and availability will be confirmed.

收尾标题：Make your next journey easier.

条件提示：Vehicle availability and fees are confirmed before booking.

### 电话卡与套餐

建议路径：/services/mobile/

设计重点：首屏正式使用学生自然使用手机的场景。合作运营商、价格、流量和 eSIM 能力未确认前不展示套餐定价表或运营商 Logo。

首屏服务名：Mobile Plans

主标题：Stay connected. From day one.

介绍：Get help choosing a SIM and mobile plan that fits your life in Australia.

全页主按钮：Explore My Options

服务内容标题：Connected from the start

- **SIM options**：Check the available SIM options for your device and arrival plans.
- **Plans for your needs**：Compare options based on data, calls, budget and length of stay.
- **Activation support**：Understand the setup steps and documents required by your provider.

三步流程：

1. **Tell us your needs**：Share your data usage, budget, device and arrival date.
2. **Explore your options**：Review available providers and plan terms with our team.
3. **Set up your service**：Complete provider requirements and follow the activation steps.

表单标题：Find your mobile options

专属字段：Arrival date；Expected length of stay（Less than 3 months / 3–12 months / Over 12 months / Not sure yet）；Monthly data needs（Light use / Regular use / High data use / Help me choose）；Preferred SIM type（Physical SIM / eSIM if supported / Not sure）；Monthly budget in AUD；Phone model。

共同字段：姓名、邮箱、电话；联系渠道至少留一种。正式实现应根据渠道选择动态显示字段，避免全部强制填写。

FAQ：

- **Can I enquire before arriving?**
  Yes. Share your arrival date so the team can explain available options and next steps.
- **Which providers and plans are available?**
  Options need to be confirmed with our team. Pricing, inclusions and terms should be reviewed before choosing a plan.
- **What documents do I need?**
  Identification and activation requirements depend on the selected provider and plan. Please do not upload identity documents with this initial enquiry.

收尾标题：Find a plan that works for you.

条件提示：Provider terms, coverage and device compatibility apply.

### 能源与网络开通

建议路径：/services/utilities/

设计重点：用明亮公寓照片；中间浅蓝横条承接“一次提交，多项服务”。服务可多选；不宣传保证入住当天开通，不默认绑定某一家供应商。

首屏服务名：Utilities Connection

主标题：Move in. Feel at home.

介绍：Get help arranging electricity, gas and internet for your new home, where available.

全页主按钮：Request Connection Support

服务内容标题：Settle in with less hassle

- **Electricity**：Explore connection options for your new address.
- **Gas**：Check whether gas service is available and needed at the property.
- **Internet**：Review connection options and installation requirements.

三步流程：

1. **Share your move**：Tell us your property address and move-in date.
2. **Choose your services**：Confirm available services, providers and relevant terms.
3. **Arrange connection**：Complete the required steps and receive timing updates.

表单标题：Get your home connected

专属字段：Property address；Move-in date；Services required（Electricity / Gas / Internet）；Property status（Moving into a rental / Already living here / Not sure）；Preferred provider；Additional details。

共同字段：姓名、邮箱、电话；联系渠道至少留一种。正式实现应根据渠道选择动态显示字段，避免全部强制填写。

FAQ：

- **When should I arrange connection?**
  Enquire before your move-in date. Timing varies by service, property and provider; internet may require an installation appointment.
- **Can I request several services together?**
  You can include electricity, gas and internet in one enquiry. Availability and connection arrangements are confirmed separately.
- **Can I choose my provider?**
  Available options depend on the address and property setup. Some buildings have specific service arrangements.

收尾标题：Moving soon? Let’s get started.

条件提示：Availability, provider terms and connection timelines vary by property.

### 房屋清洁

建议路径：/services/cleaning/

设计重点：展示三类清洁卡片；增加可展开的清洁范围，注明烤箱、地毯和外窗等需另行确认，不使用“保证退押金”。

首屏服务名：Home Cleaning

主标题：A fresher home. Less on your list.

介绍：Enquire about cleaning for everyday living, a deeper refresh or your next move.

全页主按钮：Get a Cleaning Quote

服务内容标题：Care for the space you call home

- **Regular cleaning**：Ask about cleaning for the areas you use every day.
- **Deep cleaning**：Request a more detailed clean based on the condition of your home.
- **End-of-lease cleaning**：Discuss the checklist and scope needed for your move-out inspection.

三步流程：

1. **Choose your clean**：Share the service type, address and property size.
2. **Review your quote**：Confirm scope, preferred time, exclusions and pricing.
3. **Prepare for the visit**：Arrange access and follow the agreed service instructions.

表单标题：Tell us about your cleaning needs

专属字段：Property address；Cleaning type（Regular cleaning / Deep cleaning / End-of-lease cleaning）；Preferred date；Bedrooms / bathrooms；Property condition（Light cleaning / Needs extra attention / Not sure）；Extra requests。

共同字段：姓名、邮箱、电话；联系渠道至少留一种。正式实现应根据渠道选择动态显示字段，避免全部强制填写。

FAQ：

- **What is included?**
  The final checklist is agreed with your quote. Kitchens, bathrooms, bedrooms, living areas, floors and general surfaces may be included.
- **Do I need to provide equipment?**
  Equipment, products and access arrangements will be confirmed before the visit.
- **Is end-of-lease cleaning a bond guarantee?**
  Cleaning supports your move-out preparation. Bond outcomes depend on the inspection and tenancy circumstances; a refund is not guaranteed.

收尾标题：A cleaner space starts here.

条件提示：Final scope and price depend on property size, condition and requested extras.

### 房屋维修

建议路径：/services/maintenance/

设计重点：新增草案。未确认可提供的工种，不承诺自有维修团队、24 小时响应或具体到场时效。问题分类仅用于分流，不代表全部工种均可承接。

首屏服务名：Home Maintenance

主标题：Something needs fixing? Let’s take a look.

介绍：Tell us what is happening at your property so we can help assess the next steps for maintenance.

全页主按钮：Request Maintenance Support

服务内容标题：Help with the next step

- **Report the issue**：Explain where the problem is and when it started.
- **Assess the next step**：Check the scope, access needs and any approval requirements.
- **Arrange support**：Confirm service availability, timing and fees before work proceeds.

三步流程：

1. **Describe the problem**：Share your address, issue and preferred contact details.
2. **Review the request**：Our team checks what information and approvals are needed.
3. **Confirm the arrangement**：Agree on the next step before any visit or work is arranged.

表单标题：Tell us what needs attention

专属字段：Property address；Issue category（Plumbing / Electrical / Appliance / Other / not sure）；Describe the issue；When can we contact you?；Tenant / owner（Tenant / Owner / Other）；Access availability。

共同字段：姓名、邮箱、电话；联系渠道至少留一种。正式实现应根据渠道选择动态显示字段，避免全部强制填写。

FAQ：

- **Can I request any type of repair?**
  Send a description first. Service scope and availability need to be assessed; some work requires a qualified specialist.
- **Will I need approval?**
  If you rent, landlord or property manager approval may be needed before work is arranged. Responsibility and fees should be confirmed.
- **Is this an emergency service?**
  This enquiry is not monitored as an emergency response channel. For an urgent safety issue, use your property’s emergency arrangements and the appropriate local emergency service.

收尾标题：Take the first step towards a fix.

条件提示：Work scope, approval, availability and responsibility for costs are confirmed first.

## 表单与交互实施要求

- 初次咨询只收集服务所需的基本信息。身份、护照、银行卡等资料不放在公开咨询表单中。
- 日期不能选择不合理的过去日期；电话号码支持国家代码；字段有明确标签，错误提示跟随字段；提交按钮在处理中显示状态并避免重复提交。
- 提交成功只能表示咨询已收到，说明后续联系渠道，不能表示服务已预订。失败时保留已填信息并提供重试。
- 联系同意与营销订阅分开，营销订阅不默认勾选。隐私政策须说明用途、接收方与保存安排；实际同意机制由业务确认。
- 能源服务多选；接机送机切换时变更地址与时间标签；清洁的房间数用数字选择；维修正式可增加可选照片上传，限制类型和大小并说明用途。
- 电话卡先咨询；套餐确认后才增加价格比较和运营商资料。能源开通、清洁及维修分别显示各自条件，不把不同服务条件写成全站统一保证。
- 手机端卡片纵向堆叠、表单双列改单列；不使用内部横向滚动。按钮和展开项便于触控，保留键盘焦点，文字颜色不能只依赖浅蓝区分。

## SEO 与交付要求

每页只设置一个 H1，服务卡片及流程采用合理 H2/H3 层级。为五页分别提供独立标题、描述和地址；正式站按已确认服务地区补充自然文案，不堆砌城市关键词。图片压缩并提供描述性 alt，避免在图片里写入正文。原首页保留租房主入口，服务导航链接到这五页。

设计公司交付桌面及手机端 UI、所用素材与授权来源、按钮/展开/表单错误/提交状态，以及可复用服务页面组件。先在独立预览环境中审阅，确认后由负责原站的团队实施。现有网站源码未提供，本稿不构成原站代码补丁。

## 上线前需要业务确认

- 品牌最终拼写、蓝色标准值、Logo 清晰原文件。
- 五项服务真实覆盖城市、是否自营或合作方履约、联系方式及接收咨询的人员。
- 接送机：车型、人数和行李限制、等待/延误/取消政策、报价方式。
- 电话卡：合作供应商、SIM/eSIM 能力、套餐条款、激活要求与支持范围。
- 能源：合作供应商、网络类型、建筑限制、连接周期及费用。
- 清洁：真实项目、设备、额外收费、取消/改期/返工安排。
- 维修：可承接工种、资质要求、审批流程、费用承担、紧急故障联系渠道。维修页是本次新增建议内容，需要单独审核。
