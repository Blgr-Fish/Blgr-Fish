```c++
#include <iostream>
#include <vector>

class BlgrFish : public Profile {

  private:
    // Myself
    std::string nickname = "Blgr-Fish";
    int age = 18 ;
    std::string location = "Nantes, France";

    // My skills
    std::vector<std::string> spokenLanguages = { "French", "English", "Spanish" };
    std::vector<std::string> skills = { "Python" , "C++" , "HTML" , "CSS" , "JavaScript" , "TypeScript" };
    std::vector<std::string> interests = { "CyberSecurity" , "Video Games" };

  public:
    virtual void getLinks() override {

      std::cout << "Twitter : https://twitter.com/f_ish_"  << std::endl;
      std::cout << "RootMe  : https://www.root-me.org/u5ume" << std::endl;

    }
};

```

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=blgr-fish&show_icons=true&theme=radical)
