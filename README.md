```cpp
#include <string>
#include <vector>

class PersonalInfo {
public:
      std::string nickname;
private:
      std::string fullName;
      int age;
};

class ContactInfo{
public:
      std::string telegramUsername;
      std::string tikTokUsername;
private:
      std::string phoneNumber;
      std::string email;
}

class AdditionalInfo{
public:
      std::vector<std::string> favoriteDistros;
      std::vector<std::string> favoritePL;
      std::string favoriteIDE;
}

void GoldenVadim(){
      PersonalInfo personalInfo;
      personalInfo.nickname="GoldenVadim";

      ContactInfo contactInfo;
      contactInfo.telegramUsername="@GoldenVadimOfficial"
      contactInfo.tikTokUsername="@goldenvadim"

      AdditionalInfo additionalInfo;
      additionalInfo.favoriteDistros = {"Gentoo", "Debian"};
      additionalInfo.favoritePL = {"C++", "Python"};
      additionalInfo.favoriteIDE = "Qt Creator";
}

int main()
{
      GoldenVadim();
}
```
