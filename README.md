int money = 4500;
Console.WriteLine($"деньги :{money}");
if (money <= 0)
    Console.WriteLine($"Некорректные данные");

Console.WriteLine("Скидка на джинсы");
int sale = Convert.ToInt32(Console.ReadLine());

Console.WriteLine("Цена Джинс");
int price = Convert.ToInt32(Console.ReadLine());

if (money >= price - sale && price > 0 && sale >0)
    Console.WriteLine($"Хватит");
else if (money <price - sale)
    Console.WriteLine($"Не хватит");
else if (price <= 0 || sale <= 0 )
    Console.WriteLine($"Некорректные данные");
