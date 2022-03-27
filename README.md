3주차 수업 내용 정리

1. 어댑터 안에 들어갈 각 아이템의 데이터를 담아줄 클래스 정의 : 이름, 전화번호
2. 기본생성자, get, set 메소드 생성
3. PersonAdapter클래스 생성(파일)
4. ViewHoler클래스 정의 -> RecyclerView.ViewHolder상속
5. 생성자 생성 및 객체화
6. setItem메소드 생성 : TextView의 걊을 지정
7. PersonAdapter클래스에 RecyclerView.Adapter<PersonAdapter.ViewHolder>를 상속
8. Person타입의 데이터를 담을 ArrayList자료형 선언
9. onCreateViewHolder메소드
  - LayoutInflater를 선언하여 관리자 지정 -> ViewGroup.getContext()
  - 뷰객체 생성 : 인플레이터 이용 -> inflate(인플레이션할 부분, 인플레이션한 뷰를 담을 공간, 바로 실행할 여부)
  - 뷰홀더 객체 생성 및 뷰 객체 전달
10. onBindViewHolder
  - 위치(position)을 이용해 ArrayList에서 데이터 get
  - get한 데이터를 뷰홀더에 배치
  - getItemCount() 메서드 : ArrayList자료형의 size()
11.
  - addItem() : ArrayList자료형에 Person데이터 추가
  - setItems() : ArrayList선언
  - getItem() : ArrayList에서 위치(position)으로 원하는 데이터 반환
  - setItem() : 배치
12. 레이아웃의 리사이클러뷰 객체화
13. LinearLayoutManager 생성
14. 리사이클러뷰의 레이아웃 매니저 설정
15. PersonAdapter(클래스) 객체 생성
16. -> Person객체 생성으로 어뎁터의 데이터 추가
17. 리사이클러뷰의 어댑터 설정
