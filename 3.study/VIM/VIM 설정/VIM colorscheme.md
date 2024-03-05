# VIM 색깔 바꾸기

모처럼 VIM을 사용하는데 눈에 보기 좋고 맘에 드는 색 테마를 이용하고 싶다면 colorsheme을 설정해보자.  
![Pasted image 20240305231633.png](app://92167105cc6f78ef0c80be64ab74ba5bebdf/C:/Users/SSAFY/Documents/Obsidian/media/Pasted%20image%2020240305231633.png?1709648193186)  
[https://vimcolorschemes.com/page/](https://vimcolorschemes.com/page/)  
다양한 색깔과 테마가 존재한다.
# 기본 스키마 설정
어떤 스킨이 너무 맘에 들어서 적용을 하려고 봤는데 왠걸, 그냥 내장되어 있는 것은 아닌 모양이었다. 이를 직접 설치하기에 앞서 기본적으로 적용된 스키마는 무엇이 있는지, 어떻게 설치하는지 알아볼 필요가 있다고 판단했다.
https://phoenixnap.com/kb/vim-color-schemes
```
:colorscheme [space] [Ctrl+d]
```
이런 명령어를 치면 기본적으로 사용가능한 스키마가 출력된다.
![[Pasted image 20240305234717.png]]
... 생각보다 굉장히 적다.
# 커스텀 스키마 설정
커스텀 스키마를 적용하고 싶다면 직접 다운로드를 하면 된다. 
홈 디렉터리에서 `.vim/colors`에 다운 받은 스키마를 적용하면 완료!![[Pasted image 20240306000534.png]]

이후에는 
```
set colorscheme [원하는 스키마]
```
를 쳐주거나, vimrc 파일에 명시해주면 완료!