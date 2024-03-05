# VIM 색깔 바꾸기
모처럼 VIM을 사용하는데 눈에 보기 좋고 맘에 드는 색 테마를 이용하고 싶다면 colorsheme을 설정해보자.
![[Pasted image 20240305231633.png]]
https://vimcolorschemes.com/page/
다양한 색깔과 테마가 존재한다.
내가 고르는 기본적인 조건은 다음과 같다.
- 다크 테마
- 전체적인 색은 초록색을 많이 띌 것
- 각각의 요소가 색깔로 구분은 돼야 함
- 주석이 가시적으로 볼 수 있는 수준이어야 함

나는 초록색을 좋아하기에 몇 가지 후보군을 물색했다.
1. reloaded.vim  ![[Pasted image 20240305232247.png]]
	- 이건 조금 쉽지 않은 색
2. greenwint ![[Pasted image 20240305232534.png]]
	- 이건 꽤 괜찮지만, 검은 색으로 시작이 들어가서 직관적이지는 않다.
3. phosphor ![[Pasted image 20240305232743.png]]
	- 햐.. 이건 애매하다. 괜찮을 듯 아닌 듯
4. Relaxed-Green ![[Pasted image 20240305232948.png]]
	- 지금까지 본 것 중에서는 가장 괜찮다.
5. briofita_vim ![[Pasted image 20240305233241.png]]
	- 이건 전체적인 색은 좋다.
	- 다만 아쉬운 건 프레임 색이 갈색이라는 것 정도.
6. vim-tango ![[Pasted image 20240305233553.png]]
	- 와 이것도 좋다.
7. nightvision-nvim ![[Pasted image 20240305233955.png]]
# 기본 스키마 설정
nightvision이 너무 맘에 들어서 적용을 하려고 봤는데 왠걸, 그냥 내장되어 있는 것은 아닌 모양이었다. 이를 직접 설치하기에 앞서 기본적으로 적용된 스키마는 무엇이 있는지, 어떻게 설치하는지 알아볼 필요가 있다고 판단했다.
https://phoenixnap.com/kb/vim-color-schemes
```
:colorscheme [space] [Ctrl+d]
```
이런 명령어를 치면 기본적으로 사용가능한 스키마가 출력된다.
![[Pasted image 20240305234717.png]]
... 생각보다 굉장히 적다.
# 커스텀 스키마 설정
커스텀 스키마를 적용하고 싶다면 직접 다운로드를 하면 된다. 
홈 디렉터리에서 `.vim/colors`에 다운 받은 스키마를 적용하면 완료!
```