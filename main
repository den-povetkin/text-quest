from time import sleep
from hero import Hero


knight = Hero('Ричард', 50, 25, 20, 'меч')
dragon = Hero('Дракон', 100, 25, 10, 'пламя')


print('Средиземье в опасности! На помощь спешит доблестный рыцарь...')
knight.print_info()


sleep(5)
print(knight.name + ' идёт по лесу. Вдруг видит на пути мелкого воришку...')


sleep(5)
rascal = Hero('Питер', 20, 5, 5, 'нож')
rascal.print_info()


sleep(5)
if input('Сразиться? (да/нет) >>') == 'да':
   print('\nДА НАЧНЁТСЯ БИТВА!\n')
   sleep(5)
   knight.fight(rascal)
   sleep(5)


   if knight.health > 0:
       knight.health = 50
       knight.power *= 2
       knight.armor *= 2
       print('\n' + knight.name + ' восстановил силы и стал опытнее. Теперь сила его удара: ' + str(knight.power) + ', а класс брони:' + str(knight.armor) + '\n')


sleep(5)
print('\nНаконец-то ' + knight.name + ' добирается до подземелья!')
dragon.print_info()


print('\nДА НАЧНЁТСЯ БИТВА!\n')
sleep(5)
knight.fight(dragon)
