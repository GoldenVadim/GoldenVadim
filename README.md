```cpp
#include <string>
#include <vector>

using std::string,std::vector

class PersonalInfo {
public:
      string nickname;
private:
      string fullName;
      unsigned age;
};

class ContactInfo{
public:
      string telegramUsername;
      string tikTokUsername;
private:
      string phoneNumber;
      string email;
}

class AdditionalInfo{
public:
      string favoriteDistro;
      vector<string> favoritePL;
      string favoriteIDE;
}

void GoldenVadim(){
      PersonalInfo personalInfo;
      personalInfo.nickname="GoldenVadim";

      ContactInfo contactInfo;
      contactInfo.telegramUsername="@GoldenVadimOfficial"
      contactInfo.tikTokUsername="@goldenvadim"

      AdditionalInfo additionalInfo;
      additionalInfo.favoriteDistros = "Gentoo";
      additionalInfo.favoritePL = {"C++", "Python"};
      additionalInfo.favoriteIDE = "";
}

int main()
{
      GoldenVadim();
      return 0;
}
```
