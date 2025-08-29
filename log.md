- 당분간 nlog와 기존 scroll log를 동시 전송하는건?
- DnA랑 논의해서 scroll log 기능을 얼마나 전환해야할지
- nlog로 전환되어도 거버닝 문제는 해결 필요
- pv하고 기본 트리거에 들어가는거 외에 기본적으로 들어가야 하는게 어떤거가 되는게 좋을지에 대한 기준이 다른거 같음
	- pv, scroll end, resize, expand 는 일반적으로 쓸거기 때문에 트리거를 만들어 둠
	- resize, expand domchange
	- disable 은 검색만의 이벤트라고 봄 -> 없어도 되지 않을지
	- 노출의 정의는 전사 기준으로 초안을 작성해둠 50% 이상 노출 300ms 이상 노출
- dna측 검토 
	- 없앨수 있는거 불필요한거
	- 가능하시면 다음주까지 (09 첫주)
- 방향성이 어느정도 정해지면 nlog scroll 적용해본다

<!--stackedit_data:
eyJoaXN0b3J5IjpbMzk0MjgyODc2XX0=
-->