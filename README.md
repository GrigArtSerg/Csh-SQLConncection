Пример взаимодействия с SQL-базой данных с помощью C#.

Написанная программа при запуске запрашивает параметры для подключения к базе данных (при написании использовалась MySQL). По очереди задаются параметры IP-адреса БД, номер порта, имя пользователя, пароль пользователя и имя БД.

Далее пользователю предлагается ввести одну из команд:

salary - позволяет получить информацию о суммарной зарплате сотрудников какого-либо департамента.
  После подтверждения ввода команды программа ожидает ввода нормера интересующего департамента. На данном этапе возможно получить сводку по всем департаментам вводом команды all
  Далее можно указать программе - следует ли её учитывать руководителя департамента при подсчете суммарной зарплаты. В случае некорректного ответа пользователь получит информацию со значением по умолчанию - без учета руководителя.
  
max - позволяет получить информаци о департаменте в котором зарплата сотрудника максимально

chiefs - позволяет вывести в порядке убывания зарплаты руководителей

Все команды не чувствиетльны к регистру. При вводе некорректных комманд пользователю выводится сообщение об этом/
