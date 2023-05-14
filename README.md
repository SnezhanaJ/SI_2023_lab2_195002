# SI_2023_lab2_195002
# Снежана Јанкулова, бр. на индекс 195002
# Control Flow Graph
![image](https://github.com/SnezhanaJ/SI_2023_lab2_195002/assets/127696203/0c58753a-8659-46dc-bb37-fd4de8ac88b3)

# Цикломатска комплексност
Цикломатската комплексност на овој код е 9, истата ја добив така што ги броев регионите кои се формираат од јазлите.
# Multiple Condition критериумот
if (user==null || user.getPassword()==null || user.getEmail()==null) {} 
Минималниот број на тест случаеви ќе биде 4.
Во првиот тест случај ќе провериме за user==null
Во вториот тест случај ќе провериме за user!=null a user.getPassword()==null
Во третиот тест случај user и лозинката нема да бидат null а user.getEmail()==null
И четвртиот тест случај кога ниту еден од условите нема да биде null, односно user!=null, user.getPassword()!=null и user.getEmail()!=null
