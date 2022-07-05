# Insertion Sort Projesi

## Soru 1:
### **[22,27,16,2,18,6]** -> Insertion Sort

- Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
- Time Complexity, Average Case, Worst Case, Best Case durumlarını inceleyiniz.
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Cevaplayınız.
----------------------------------------------------------------------------------------------------------------------------------------------------------
## Cevap 1.1: 
- 1. Aşama: [**2**,27,16,**22**,18,6] 
- 2. Aşama: [2,**6**,16,22,18,**27**]
- 3. Aşama: [2,6,16,22,18,27]
- 4. Aşama: [2,6,16,**18**,**22**,27]
- 5. Aşama: [2,6,16,18,22,27]
----------------------------------------------------------------------------------------------------------------------------------------------
## Cevap 1.2:
[22,27,16,2,18,6] dizisinin Big-O notasyonu (n.(n+1))/2 işleminden
O(n²) --> O(5²) = O(25) olacaktır.

-----------------------------------------------------------------------------------------------------------------------------------------------
## Cevap 1.3:
### Time Complexity
- Best Case: Dizinin sıralı olması -> n
- Worst Case: Dizinin tersten sıralı olması -> n²
- Average Case: Dizinin rastgele dağılımı -> n²
----------------------------------------------------------------------------------------------------------------------------------------------
## Cevap 1.4:
- Dizinin sıralı hali -> [2,6,16,18,22,27]
- 18 sayısı dizinin ortadaki elemanlarından biridir.
- Bu nedenle **Average Case** kapsamına girer.

---------------------------------------------------------------------------------------------------------------------------------------- 
## Soru 2: 
### **[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
--------------------------------------------------------------------------------------------------------------------------------------------------------
1. Adım: [**2**,3,5,8,**7**,9,4,15,6] -> 2 ile 7 yer değiştiriyor.
2. Adım: [2,3,5,8,7,9,4,15,6] -> 3 elemanı doğru yerde olduğu için değişiklik yapılmıyor.
3. Adım: [2,3,**4**,8,7,9,**5**,15,6] -> 4 ile 5 yer değiştiriyor.
4. Adım: [2,3,4,**5**,7,9,**8**,15,6] -> 5 ile 8 yer değiştiriyor.