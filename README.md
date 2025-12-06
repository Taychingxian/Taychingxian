<h2 align="left">Hi 👋! My name is TAY CHING XIAN and I'm a 3rd year CS student</h2>

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=250&section=header&text=Tay%20Ching%20Xian&fontSize=80&fontColor=ffffff&desc=CS%20Student%20|%20Dev%20|%20Binary%20Enthusiast&descSize=25&descAlign=50&animation=fadeIn)

<div align="center">

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2094F7&center=true&vCenter=true&width=435&lines=Hi!+I'm+Tay+Ching+Xian;Debugging+Life...+;I+speak+Binary+(1%2B1%3D10);Always+Learning..." alt="Typing SVG" />
  </a>

  <p>
    <a href="https://youtube.com/YOUR_CHANNEL_LINK">
      <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
    </a>
    <a href="https://instagram.com/YOUR_INSTA_HANDLE">
      <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
    </a>
    <a href="https://twitch.tv/YOUR_TWITCH_HANDLE">
      <img src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white" />
    </a>
    <a href="mailto:YOUR_EMAIL@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
  </p>

</div>

---

### 👨‍💻 `user_profile.cpp`

```c++
#include <iostream>
#include <vector>

class TayChingXian {
public:
    std::string name = "Tay Ching Xian";
    std::string role = "CS Student (Year 3)";
    std::string location = "Malaysia";
    std::string humor = "Binary (1+1=10)";

    void current_status() {
        std::cout << "Loading future software engineer..." << std::endl;
        std::cout << "Status: Fueled by coffee and bugs." << std::endl;
    }

    std::vector<std::string> skills() {
        return { "C", "C++", "HTML5", "CSS3", "Python" };
    }
};

int main() {
    TayChingXian me;
    me.current_status();
    return 0;
}
