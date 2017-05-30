# lab6

1.

(1)true

(2)false, the is-a relationship represents inheritance.

(3)false, a student class has a has-a relationship with the Faculty and Course classes.因為學生是屬於這兩個class的一部份，而不是一種

(4)false, 可以存取，只是在derived class中，是private。

(5)true

---

2.

                                    Student

                                 ↗           ↖

                 UndergraduateStudent          GraduateStudent
                 
            ↗        ↗       ↖     ↖             ↗             ↖

    Freshman   Sophomore   Junior   Senior    DoctoralStudent   MasterStudent

                                  ↗   ↑   ↖ 
 
                          攻讀研究所 找工作 延畢

                            ↗   ↖  

                        推薦甄試  筆試

推薦甄試生跟筆試生繼承了攻讀研究所的人

攻讀研究所、找工作、延畢這三類人都屬於在為大四下一年做準備的出路，所以繼承大四

Freshman、Sophomore、Junior、Senior都屬於大學部，所以繼承UndergraduateStudent；而DoctoralStudent、MasterStudent都屬於研究所，所以繼承GraduateStudent

UndergraduateStudent、GraduateStudent都是大學的學生，所以繼承Student
