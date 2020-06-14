# 项目说明
web自动化项目

# 环境准备
- windows
- python3.6
- pytest4.5.1
- allure

# 安装依赖包
使用pip安装依赖包
> pip install -r requirements.txt

# 运行用例
运行用例，生成报告在./report/allure_report
> pytest --alluredir ./report/allure_report

# 生成allure报告
启动allure服务查看报告
> allure serve ./report/allure_report