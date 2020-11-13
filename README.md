Dizi Karşılaştırma

Parametre olarak aldığı iki tamsayı dizisinin elemanlarının ilk n tanesinin toplamının eşit
olup olmadığını karşılaştıran compareNthSum isimli bir metot yazınız. Metot eğer ilk n elemanın toplamı aynıysa n döndürmelidir (birden fazla eleman sayısı için toplamlar eşit oluyorsa maksimum n’yi döndürmelidir) Böyle bir n yoksa metot -1 döndürmelidir.
Örneğin:

• arr1 = {1,2,3,4,5} ve arr2 = {4,1,1,7,8} dizilerinin her ikisinin de ilk 3 elemanının toplamı 6’dır dolayısıyla compareNthSum(arr1,arr2) 3 döndürmelidir.

• arr1 = {1,3,7} ve arr2 = {1,8,6} dizilerinin her ikisinin de ilk 1 elemanının toplamı 1’dir dolayısıyla compareNthSum(arr1,arr2) 1 döndürmelidir.

• arr1 = {3,4,3,4,5,6} ve arr2 = {2,5,1,6,8,1} dizilerinin her ikisinin de ilk iki elemanının toplamı 7’dir ancak ilk dört elemanın toplamları da aynı(14) olduğundan compareNthSum(arr1,arr2) 2 değil 4 döndürmelidir.

• Karşılaştırılan dizilerin uzunluklarının aynı olmasışart değildir. arr1 = {2,1,3,4,5} ve arr2 = {1,4,1,8}dizilerinin uzunlukları aynı değildir ancak her ikisinin de ilk üç elemanının toplamı 6’dır dolayısıyla compareNthSum(arr1,arr2) 3 döndürmelidir.

• arr1 = {1,2,3}ve arr2 = {7,10,8} ise compareNthSum(arr1,arr2) -1 döndürmelidir.

Yazdığınız bu metodu test eden bir Java programı yazınız.

Programın çıktısı {1,2,3} ve {7,10,8} dizileri için aşağıdaki gibi:
n sayisinin hicbir degeri icin {1,2,3} ve {7,10,8} dizilerinin ilk n elemanının toplamı aynı değildir.

{3,4,3,4,5,6} ve {2,5,1,6,8,1} dizileri için aşağıdaki gibi olmalıdır:
{3,4,3,4,5,6} ve {2,5,1,6,8,1} dizilerinin maksimum ilk 4 adet elemanının toplamı aynıdır.
