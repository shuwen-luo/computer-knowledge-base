# Word 转 PDF

## 1. 适用场景
Word 无法正常使用，需要将 DOCX 转换为 PDF。

## 2. 所需工具
LibreOffice
官网：https://www.libreoffice.org/

## 3. 操作步骤
1. 下载并安装与所在硬件环境对应的 LibreOffice。在系统信息里查看系统类型，基于x64就是前者，基于arm64就是后者。一般来说win本基于x64，macbook基于arm64。
<img width="980" height="536" alt="image" src="https://github.com/user-attachments/assets/ac8fa654-d610-4d83-9985-8f9df0225a51" />
<img width="720" height="203" alt="image" src="https://github.com/user-attachments/assets/f3059814-d015-4b3d-9924-8b409bea4cce" />

自MacBook air以来苹果转向自主研发M芯片，之前是intel芯片
<img width="1171" height="554" alt="Screenshot 2026-11-10 at 10 30 09" src="https://github.com/user-attachments/assets/f75d37f9-f256-495a-9e16-656d12161595" />
<img width="320" height="54" alt="Screenshot 2026-11-10 at 10 21 46" src="https://github.com/user-attachments/assets/b5e2f66f-4547-4f3c-9419-260a622dc257" />


2. 打开文件所在文件夹，点击资源管理器顶部的地址栏，输入 powershell，按回车。这样可以直接检索到该文件的绝对路径。
<img width="1066" height="506" alt="image" src="https://github.com/user-attachments/assets/f1b9d2ad-a08c-41e1-b798-085cd5a52c01" />
<img width="521" height="149" alt="image" src="https://github.com/user-attachments/assets/8f46238a-7fd6-4953-a160-24a53c975895" />

3. 输入格式 & "soffice.exe的绝对地址" --headless --convert-to pdf --outdir . "要转换的word文件"。
例如：& "C:\Program Files\LibreOffice\program\soffice.exe" --headless --convert-to pdf --outdir . "实验报告.docx"
<img width="864" height="146" alt="image" src="https://github.com/user-attachments/assets/d5288591-2115-4fea-8aaa-d381d08201cb" />
<img width="507" height="44" alt="image" src="https://github.com/user-attachments/assets/2d36bc01-73aa-4269-ad80-bf510674818e" />

4. 检查 PDF 是否正常。

