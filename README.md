# Practice

		Scanner sc = new Scanner(System.in);
		int Kor= 0, Eng=0, Math=0;
		
		System.out.print("국어점수 ==> ");
		Kor = Integer.parseInt(sc.nextLine()); //엔터칠때까지 치는걸 받아오는거임
		System.out.print("영어점수 ==> ");
		Eng = Integer.parseInt(sc.nextLine());
		System.out.print("수학점수 ==> ");
		Math = Integer.parseInt(sc.nextLine());
		
		System.out.println("총점 :" + (Kor+Eng+Math));
		System.out.println("평균 :" + (Kor+Eng+Math)/3.0);
