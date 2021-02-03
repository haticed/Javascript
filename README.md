// Output
//alert('merhaba')
//document.write('ders')
//document.querySelector('p').innerHTML='derse başladık'
​
console.log('isa')
 console.error('hata var')
// console.warn('Dikkat et')
​
/*
Değişken
Veri türleri
operatör
atama kavramı
koşullu ifadeler
döngü
functions
event
DOM
*/
​
// var isim = "isa";
// isim = "mehmet"
// console.log(isim)
// var sayi = 23
// console.log(sayi)
// var soyisim;
// console.log(soyisim)
​
// let ve const
​
// var x = 40
// var y = 50
// var toplam = x + y
// console.log(toplam)
​
//var 1isim = "isa" geçersiz
​
// var _isim = "isa" geçerli
// var $isim = "mehmet"    geçerli
// var *isim = "isa"   geçersiz
​
// var takimAdi = "galatasaray"
​
​
//************************ */
//       DEğişken Türleri
​
/*
​
Primitive types: String, Number, Boolean, undefined
​
Reference Types: Object, Array, Functions
​
*/
​
// STRING
​
// let isim = "isa"
// isim = 'cenk'
​
// console.log(typeof(isim))
​
//       NUMBER
​
//let yas = 36
//console.log(yas)
​
// var maas = 21.5
// console.log(typeof maas)
​
//      BOOLEAN
​
// var done = true
// console.log(done)
​
//         Undefined
​
// let isim;
// console.log(isim)
​
​
//             ARRAYS
​
// let isimler = [1,3,5,7, "isa", "cenk"]
// // console.log(typeof isimler)
//  console.log(isimler.length)
​
​
//       OBJECT
​
// let bilgiler = {
//     isim : 'isa',
//     soyisim : 'Acarer',
//     dil : 'Javascript',
//     yas : 36,
//     evli_mi : true
// }
​
// console.log(bilgiler['soyisim'])
// console.log(bilgiler.dil)
// console.log(typeof bilgiler)
​
//   FUNCTIONS
​
// var topla = function(a,b){
//     return a+b
// }
​
// //console.log(typeof topla)
​
// console.log(topla(1,5))
​
//  NULL
​
// var insan = {
//     isim:"isa",
//     soyisim : "Acarer",
//     yas : 36
// }
// console.log(insan)
​
// insan = null
​
// console.log(insan)
​
// *************************************
​
//      VERİ TİPİ DÖNÜŞÜMLERİ
​
​
// let x = "45"
// let y = 20
​
// let toplam = Number(x) + y
​
// console.log(toplam)
​
// let sayi = 45
// let yenideger = String(sayi)
​
// console.log( typeof yenideger)
​
​
// let deger =true
// deger = String(deger)
// console.log(typeof deger)
​
// let tarih = new Date()
​
// console.log(tarih)
// console.log(tarih.getFullYear())
// console.log(typeof tarih)
// tarih = String(tarih)
// console.log(tarih)
// console.log(typeof tarih)
​
// var isimler = ["isa", "mehmet", 36]
// console.log(typeof isimler)
// isimler = String(isimler)
// console.log(typeof isimler)
​
// let x = 10
// x = (x).toString()
// console.log(typeof x)
​
// let deger = Number([1,2,3,4])
​
// console.log(deger)
// console.log(typeof deger)
​
// let deger = parseFloat('4.3') // parseInt
// console.log(deger)
// console.log(typeof deger)