# Программа "BankApp"
 Программа регистрации и входа пользователя в банк

Выполнил: Ионин Данила Вадимович

Интерфейсы приложения:

![LoginPage](/ImagesBank/LoginPage.png "Страница авторизации")
![Registration](/ImagesBank/RegistrationPage.png "Страница регистрации")

Класс "UserData" используется для регистрации нового пользователя в банке
```
namespace GymApp.Classes
{
    internal class ClassHelper
    {
        public static int ModeGender = 0;
    }
}
```

Класс "UserDataRepository" используется для хранение информации об уже зарегестрированных пользователях
```
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Bank
{
    internal class UserDataRepository
    {
        public List<UserData> userDatas = new List<UserData>();
    }
}
```
