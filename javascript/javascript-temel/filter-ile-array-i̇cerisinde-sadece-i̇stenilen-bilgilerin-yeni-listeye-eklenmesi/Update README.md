# Filter ile Array İçerisinde Sadece İstenilen Bilgilerin Yeni Listeye Eklenmesi

Filter() yöntemi, belirlenen koşulları geçen boolean ifadeye göre dizi elemanlarının yeni oluşacak diziye aktarmayı sağlar.

### Alıştırmalar
Hece sayısı 8'den büyük olan kelimeleri getiren filter() kodu:
```javascript
const kelimeler = ['Matematik', 'Kimya', 'Biyoloji', 'İngilizce', 'Türkçe'];

const sonuc = kelimeler.filter(kelime => kelime.length > 8);
console.log(sonuc);
```
[Codepen'de deneyin](https://codepen.io/selindayioglu/pen/ZEpobaa)


5'den küçük olanları getiren filter() kodu:
```javascript
var dizi = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
var yeniDizi = dizi.filter(function (sayi) {
    if (sayi < 5) {
        return true;
    }
});
console.log(yeniDizi);
```
[Codepen'de deneyin](https://codepen.io/selindayioglu/pen/wvzjMad)
