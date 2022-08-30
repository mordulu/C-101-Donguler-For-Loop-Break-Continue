[Patika.dev](https://github.com/mordulu)


Dosyalarımın içinde yer alan program.cs'ye girilme zahmeti olmaması adına aşağıya çalışmamı önizleme olarak ekliyorum(süslü parantezler önizlemede hata verdiğinden konumlandırmalarına dikkat etmeyiniz)

# C-101 Donguler-For-Loop-Break-Continue

    internal class Program
    {

    //Ekrandan girilen sayıya kadar olan tek sayıları ekrana yazdır.
    //System.Console.WriteLine("Lütfen bir sayı giriniz:");
    //int sayac = int.Parse(Console.ReadLine());
    //for (int i =0; i <= sayac; i++)
    //{
    //    if(i%2 == 1)
    //        Console.WriteLine(i);
    //    //komutlar
    //
    //
    //}
    //
    //// 1 ile 1000 arasındaki tek ve çift sayıların değişken içlerinde toplamlarını ekrana yazdır.
    //int tekToplam = 0;
    //int çiftToplam = 0;
    //for (int i = 0; i <= 1000; i++)
    //{
    //
    //    if(i%2 == 1)
    //        tekToplam += i; // tekToplam = tekToplam + i;
    //    else
    //        çiftToplam += i; // tekToplam = tekToplam + i;
    //}
    //System.Console.WriteLine("Tek Toplam: " + tekToplam);
    // System.Console.WriteLine("Çift Toplam: " + tekToplam);

    //break, continue
    //}



    private static void Main(string[] args)
    {
        for (int i = 1; i < 10; i++)
        {
            if (i == 4)
                break;
            Console.WriteLine(i);
        }

        for (int i = 1; i < 10; i++)
        {
            if (i == 4)
                continue;
            Console.WriteLine(i);
        }
    }
    }
