# ������HTML�¼�
`onchange`-HTMLԪ�ظı�  
`onclick`-�û����HTMLԪ��  
`onmouseover`-�û���һ��HTMLԪ�����ƶ����
`onmouseout`-�û���һ��HTMLԪ�����ƿ����   
`onkeydown`-�û����¼��̰���   
`onload`-����������ҳ��ļ���   
# �ַ����е����Ų�Ҫ���ַ�����������ͬ
�ַ������� `.length`  
# ת���ַ�
`\b`-�˸�  
`\f`-��ҳ  
`\r`-�س�  
`\n`-����  
`\t`-tab  
`\"`-��  
# �ַ�������
1. constructor-���ش����ַ������Եĺ���,constructor���Է��ر��������Ĺ��캯��  
2. length-�����ַ����ĳ���
3. prototype-���������������Ժͷ���
# �߼������
* &&-and   
* ||-or  
* !-not  

# ѭ��
for/in-ѭ���������������

# typeof������
����������������   
`typeof null`����object��  
`null==undefined`-true;  
������һ������Ķ������ͣ�  
# Javascript����ת��
* `Number()`ת��Ϊ����
* `String()`ת��Ϊ�ַ���
* `Boolean()`ת��Ϊ����ֵ
# Javascript��������
### 5����������
1. string
2. number
3. boolean
4. object
5. function
### 3�ֶ�������
1. Object
2. Date
3. Array    
### 2�������κ�ֵ����������
1. null
2. undefined
# ʹ��constructor�������鿴�����Ƿ�Ϊ����
`function isArray(myArray){
	return myArray.constructor.toString().indexof("Array")>-1;
}`
# Javascript������ʽ(Regular Expression),��дregex��regexp����RE
ʹ�õ����ַ�����������ƥ��һϵ�з���ĳ���䷨������ַ�������ģʽ��  
����ģʽ�������ı�������search(),������ʼλ�ã����ı��滻��replace()��   
### �﷨
/������ʽ����/���η�(��ѡ)
### ������ʽ���η�
`i`-ִ�жԴ�Сд�����е�ƥ��
`g`-ִ��ȫ��ƥ�䣨�������е�ƥ�䣩
`m`-ִ�ж���ƥ��
