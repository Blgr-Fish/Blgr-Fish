```c++
#include <iostream>
#include <vector>

class BlgrFish : public Profile {

private:
  std::string nickname = "Blgr-Fish";

  std::vector<std::string> skills = { "Python" , "C++" , "HTML" , "CSS" , "JavaScript" , "TypeScript" };

  std::vector<std::string> interests = { "CyberSecurity" , "Video Games" };

public:
  virtual void getLinks() override {

  std::cout << "Twitter : https://twitter.com/f_ish_"  << std::endl;
  std::cout << "RootMe  : https://www.root-me.org/u5ume" << std::endl;

  }
  

};

```
