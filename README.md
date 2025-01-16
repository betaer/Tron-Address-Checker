# Tron-Address-Checker 波场地址靓号检测

## 中文
### 名称: 波场地址靓号检测
### 介绍:
[波场地址检测](https://github.com/betaer/Tron-Address-Checker/)是一款专用工具，用于验证波场（TRON）区块链地址是否为靓号或符合特定模式（例如尾号连续相同字符的数量）。该工具可以帮助用户快速判断地址是否符合其需求，是波场爱好者和对地址模式感兴趣的开发者的理想选择。

### 示例说明
### [demo.txt](https://github.com/betaer/Tron-Address-Checker/blob/main/demo.txt) 是导入用的测试样本；
A列,B列

f00b922fa87927a93b334bbc4e01bc346d3b5a8f58c5f617c508ccc183fa4c5a,TRkWZTP7V62pLu4Y2rtEZHox7Miiiiiii
f00b922fa882a23d3b334bb4e01bc326e3b5a8f57c5f6c7c508ccc22183fb1b0,TKf4HeQc5xK1MBZxecd4Y9Pr1g9BBBBBBB
f00b922fa86bf3503b334bb4e01bc326e3b5a8f57c5f6c7c508ccc22183fc386,TRnKjc4rJbfbhufjDXec7XdRiyGzzzzzzz
b019ad18fdecfd8d9004e2095e3ce2ebe16825a802cc4d0bb564b7567e774128,TLBPs8mapSehTJLiRZ1QtzwSEQrrrrrrrr

### [demo-checked.txt](https://github.com/betaer/Tron-Address-Checker/blob/main/demo-checked.txt) 是检测后导出的样本；
A列,B列,C列 (B列末尾重复次数)

f00b922fa87927a93b334bbc4e01bc346d3b5a8f58c5f617c508ccc183fa4c5a,TRkWZTP7V62pLu4Y2rtEZHox7Miiiiiii,7
f00b922fa882a23d3b334bb4e01bc326e3b5a8f57c5f6c7c508ccc22183fb1b0,TKf4HeQc5xK1MBZxecd4Y9Pr1g9BBBBBBB,7
f00b922fa86bf3503b334bb4e01bc326e3b5a8f57c5f6c7c508ccc22183fc386,TRnKjc4rJbfbhufjDXec7XdRiyGzzzzzzz,7
b019ad18fdecfd8d9004e2095e3ce2ebe16825a802cc4d0bb564b7567e774128,TLBPs8mapSehTJLiRZ1QtzwSEQrrrrrrrr,8



## EN
### Name:Tron-Address-Checker
### Description:
[Tron-Address-Checker](https://github.com/betaer/Tron-Address-Checker/) is a specialized tool for validating TRON blockchain addresses to identify vanity addresses or those with specific patterns, such as consecutive identical characters at the end. It helps users quickly determine if a given address meets their desired criteria, making it ideal for TRON enthusiasts and developers interested in address pattern analysis.
### Example Description
### [demo.txt](https://github.com/betaer/Tron-Address-Checker/blob/main/demo.txt) is a test sample for import.
Column A,Column B 

f00b922fa87927a93b334bbc4e01bc346d3b5a8f58c5f617c508ccc183fa4c5a,TRkWZTP7V62pLu4Y2rtEZHox7Miiiiiii
f00b922fa882a23d3b334bb4e01bc326e3b5a8f57c5f6c7c508ccc22183fb1b0,TKf4HeQc5xK1MBZxecd4Y9Pr1g9BBBBBBB
f00b922fa86bf3503b334bb4e01bc326e3b5a8f57c5f6c7c508ccc22183fc386,TRnKjc4rJbfbhufjDXec7XdRiyGzzzzzzz
b019ad18fdecfd8d9004e2095e3ce2ebe16825a802cc4d0bb564b7567e774128,TLBPs8mapSehTJLiRZ1QtzwSEQrrrrrrrr

### [demo-checked.txt](https://github.com/betaer/Tron-Address-Checker/blob/main/demo-checked.txt) is a sample exported after detection.
Column A,Column B,Column C (Suffix Repeat Count of Column B) 

f00b922fa87927a93b334bbc4e01bc346d3b5a8f58c5f617c508ccc183fa4c5a,TRkWZTP7V62pLu4Y2rtEZHox7Miiiiiii,7
f00b922fa882a23d3b334bb4e01bc326e3b5a8f57c5f6c7c508ccc22183fb1b0,TKf4HeQc5xK1MBZxecd4Y9Pr1g9BBBBBBB,7
f00b922fa86bf3503b334bb4e01bc326e3b5a8f57c5f6c7c508ccc22183fc386,TRnKjc4rJbfbhufjDXec7XdRiyGzzzzzzz,7
b019ad18fdecfd8d9004e2095e3ce2ebe16825a802cc4d0bb564b7567e774128,TLBPs8mapSehTJLiRZ1QtzwSEQrrrrrrrr,8

