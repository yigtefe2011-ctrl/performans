# performans
ödev
1 ödev 
gun = input("Bir gün yaz (örnek: pazartesi): ").lower()

hafta_ici = ["pazartesi", "salı", "çarşamba", "perşembe", "cuma"]

hafta_sonu = ["cumartesi", "pazar"]

if gun in hafta_ici:

    print("Hafta içi")

elif gun in hafta_sonu:

    print("Hafta sonu")

else:

    print("Geçersiz gün girdin")

2ödev
fiyat=float(input("Ürünün fiyatını gir: "))

indirim fiyat * 0.10

indirimli_fiyat = fiyat indirim

print("İndirim miktarı:", indirim) print("İndirimli fiyat:", indirimli_fiyat)
3ödev
adet=int(input("Kaç kez yazılsın: "))

for i in range(adet): 
    print("selâ sala")
4ödev
sayilar input("Sayıları aralarında boşluk olacak şekilde gir: ")

liste sayilar.split()

ciftler =

for s in liste: 
    sayi int(s)
     if sayi % 2 == 0: ciftler.append(sayi)

if len(ciftler) > 0: 
    print("Çift sayılar:", ciftler)

else:

    print("Çift sayı yok")
ödev5 
sayilar input("Sayıları aralarında boşluk olacak şekilde gir: ")

liste sayilar.split()

for sin liste:

    sayi int(s)

    if sayi 2:

        print(sayi, "asal sayı değildir")

    else:

        asal = True

        for i in range(2, sayi):

            if sayi % i == 0:

                asal=False

                break

        if asal:

            print(sayi, "asal sayıdır")

        else:

            print(sayi, "asal sayı deil")

son
