# howto-use-jupyterlab-notebook

# JupyterLab & Jupyter notebook 사용법
> JupyterLab을 사용할 것.(Jupyter notebook 보다 기능 풍부)

## 키보드 입력모드
- Edit Mode : 셀에 입력 가능, 초록색 셀 테두리
- Command Mode : 키보드 명령 가능, 파란색 셀 테두리

## 단축키
### Command Mode 단축키
> - jupyter Notebook 키보드 단축키 : H

#### 셀 타입(Command Mode 단축키)
- Markdown : m
- Code : y   (좌측에 In[]로 표시됨)

#### 셀 다루기(Command Mode 단축키)
- 모드 변경
  - Edit Mode : Enter
  - Command Mode : Esc, Ctrl + m 
    
- 셀 추가
  - 현재 셀 위에 추가: a
  - 현재 셀 아래 추가: b
    
- 셀 삭제
  - 현재 셀 삭제: dd
  - 셀 삭제 취소: z

- 셀 복사
  - 현재 셀 복사: c  

- 셀 붙여넣기
  - 현재 셀 위에 붙여넣기: shift + v
  - 현재 셀 아래 붙여넣기: v
    
- 셀 선택 : k, j, up, down

#### 코드 실행하기
- 현재 셀을 실행하고 아래 셀 선택: Shift + Enter
- 현재 셀을 실행하기: Ctrl + Enter
- 현재 셀을 실행하고 아래 셀 추가: Alter + Enter    

#### Heading(Command Mode 단축키)
> `#`이 숫자의 갯수 만큼 입력됨
```
# change cell to heading 1
## change cell to heading 2
### change cell to heading 3
#### change cell to heading 4
##### change cell to heading 5
###### change cell to heading 6
```

### Edit Mode 단축키
- *Esc, Ctrl-M : command mode로 전환*  

- *Tab : code completion or indent*
- *Shift + Tab : tooltip*
  
- *Down : 커서를 현재 줄의 처음으로 이동, move cursor down*
- *Up : 커서를 현재 줄의 끝으로 이동, move cursor up*
  
- Ctrl + Z : undo
- Ctrl + D : delete whole line

- Ctrl + Left : go one word left
- Ctrl + Right : go one word right

- Ctrl + Shift + Minus : split cell at cursor(s)
- Ctrl + S : Save and Checkpoint

## 도움말 보는 법
- ?         -> Introduction and overview of IPython's features (this screen).
- object?   -> Details about 'object'.(?word or word?) 
- object??  -> More detailed, verbose information about 'object'.(?word or word?)
- %quickref -> Quick reference of all IPython specific syntax and magics.
- help      -> Access Python's own help system.(help(print))

> If you are in terminal IPython you can quit this screen by pressing `q`.

- Magic commands: type %magic for information on the magic subsystem.
  * %lsmagic : Magic command의 전체 명령어 list
  * %magic : Magic function 의 도움말
  * %ls
