## Pertanyaan

> Kalian diminta untuk membuat sebuah backend services untuk menerima sebuah data kecepatan, latitude dan longitude dalam sebuah body json. Dan kalian juga diharapkan untuk menyimpan data tersebut beserta dengan timestampnya.

### Expected Body
```json
{
    "kecepatan": 90,
    "latitude": 6.2088,
    "longitude": 106.8456
}
```

### Expected data yang disimpan dalam database mongodb
* ID transaksi
* kecepatan
* latitude
* longitude
* timestamp

## Jawab
1. Untuk script json disimpan di file ```bodyJson.py```
2. Expected body menggunakan Postman
![Screenshot 2022-08-19 164255](https://user-images.githubusercontent.com/107124396/185592075-229dbf83-aafe-4fc7-85d6-3c7d760d3b18.png)
3. Untuk script menyimpan data ke mongodb disimpan di file ```db_location.py```
4. Tampilan di web ```mongodb```
![2022-08-19](https://user-images.githubusercontent.com/107124396/185592426-3bcccc46-d73a-4f82-bd71-e351123d64af.png)

