![MasterHead](https://github.com/bhushanMahajan460/bhushanMahajan460/assets/68232386/ba8ad39c-e599-4b26-aa8b-8b1ea32e75ea)

<h2 align="center">Hi 👋, I'm Bhushan Mahajan 🫱🏻‍🫲🏽</h2>
<h3 align="center"> DSA in C++ || 800+ on Leetcode || ML Enthusisat || Problem Solving </h3>
<!-- <img align="right" alt="Coding" width="400" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQdPDutTVPa6nDOASI4rXp-L3YwlLYcZjXmAm-xaqYnRnf8vNKnMueAlAkpkbysUvgi5NU&usqp=CAU"> -->

<h3 align="left"> About Me </h3>

```cpp
class Student{
public:
  virtual void current_Status(string college, string degree, int cgpa, string name, string year ) = 0;
  virtual void technical_Skills( vector<string> s ) = 0;
  virtual void Coding( vector<pair<string,string> p ) = 0;
  Student(){}  
};
class journey_Begins{
  public:
  virtual void current_Status( string college, string degree, int cgpa, string name, string year ){
    cout << "One should be curious in trying innovative ideas to solving complex problems" << endl;
    cout << Hello Everyone, I am " << name << "a" << year << "student. Currenlty pursuing "<< degree << "from" << college << " with CGPA " << cgpa << endl;
  }
  virtual void technical_Skills( vector<string> &s ){
    cout << "Learning Never Stops! :D "<< endl;
    cout << "My Technical Skills includes : " ;
    for( auto &it : s ) cout << it << " " ;
  }
  virtual void Coding( vector<string> &c ){
    cout << "Learning Never Stops! :D "<< endl;
    cout << "My Coding Profiles are : " ;
    for( auto &it : c ) cout << it.first << ":" << it.second << endl; 
  }
};
int main(){
  Student *s;
  journey_begins jb;

  s = &jb;
  s -> education("Vellore Institute of Technology", "Integrated M.Tech Computer Science Specilaization in AI & ML",
                 "Bhushan Mahajan", 8.63, "Final year");
  s -> skills( {"C++", "Python", "SQL", "ReactJS"} );
  s -> coding( { "LeetCode", "https://leetcode.com/Bhushan_Mahajan/" },
               { "GFG", "https://auth.geeksforgeeks.org/user/bhushanmahajan460/practice" },
               { "HackerRank", "https://www.hackerrank.com/bhushanmahajan41" },
               { "InterviewBit", "https://www.interviewbit.com/profile/bhushan-mahajan_894" } );
  return 0;
}
```

📄 Know about my experiences -> [Resume Link](https://drive.google.com/file/d/15HVpEdBvZDBwG-s896-sVkU3TKHHqYHp/view?usp=sharing)

📩 Email me At -> [bhushanmahajan460@gmail.com](mailto:bhushanmahajan460@gmail.com)

<div align="center">
<a href="https://github.com/bhushanMahajan460?tab=repositories" target="_blank">
<img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
</a>
<a href="https://twitter.com/BhushanM46" target="_blank">
<img src=https://img.shields.io/badge/twitter-%2300acee.svg?&style=for-the-badge&logo=twitter&logoColor=white alt=twitter style="margin-bottom: 5px;" />
</a>
<a href="https://www.linkedin.com/in/bhushanmahajan460" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
<a href="https://instagram.com/bhushan19mahajan" target="_blank">
<img src=https://img.shields.io/badge/instagram-%23000000.svg?&style=for-the-badge&logo=instagram&logoColor=white alt=instagram style="margin-bottom: 5px;" />
</div>  



