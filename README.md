# IMX6ULL
IMX6ULL底板，核心版是某火IMX6ULL BTB核心板  
已知BUG1：PMIC_ON_REQ拉低后，核心板UART1引脚会通过CH340G向3.3V外设供电倒灌电流，要加隔离  
已知BUG2：POWEROFF后，核心板会通过某些外设引脚向3.3V外设供电倒灌电流  
