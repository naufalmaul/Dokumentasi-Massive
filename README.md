<div align="center">
<img src="https://github.com/naufalmaul/Dokumentasi-Massive/assets/160560916/01ba6bcb-7d06-401c-ba9a-9d11f4bd5339" align="center" style="width: 100%" />


# <div align="center">Hello mentor and visitors!👋</div>  
  

We are currently mentee from IBM Academy: Advance AI👾  
  

This is our documentation about our Massive Project: Contextual Sentiment Analysis Chatbot🥳  
  

Member of the group 28:  
  

- 🙋‍♂️ Budi Cahyono - Universitas Lampung  
  

- 🙋 Divaza Almanda Safhitri - Politeknik Negeri Medan  
  

- 🙋‍♂️ Naufal Maulana Faza - Universitas Swadaya Gunung Jati  
  

- 🙋‍♂️ Muhammad Azka Adhitama - Universitas Pendidikan Indonesia  
  

## Chatbot Documentation  
  

Pada awalan, kami menggunakan transformers lalu mengimport beberapa library seperti pipeline, auto tokenizer dan auto model for sequence classification.
Kami juga menggunakan model yang "pretrained".  
  
![](https://github.com/naufalmaul/Dokumentasi-Massive/assets/160560916/867dbbbb-f160-46c3-bd56-990ece54abe9)  
  

Pada tahap ini kami memangil fungsi untuk melakukan sentiment analysis dengan membuat beberapa label index yaitu: positif, negatif dan netral.  
  

![](https://github.com/naufalmaul/Dokumentasi-Massive/assets/160560916/5f529f51-0d7f-4e2f-aeaa-31506dfc36e7)  
  

Dilanjutkan dengan kami mengimpor library random lalu kami melakukan set-up untuk respon apa saja yang akan dikeluarkan sesuai label yang di deteksi oleh si model.  
  

![](https://github.com/naufalmaul/Dokumentasi-Massive/assets/160560916/e20da385-d8ab-4aeb-9e02-18c91d051cd4)  
  

Pada tahap ini kami melakukan permisalan sesuai dengan sentimen yang di deteksi oleh model.  



![](https://github.com/naufalmaul/Dokumentasi-Massive/assets/160560916/ce67cec1-4cb9-45ac-8880-f25dea382a29)  
  

Akhirnya kami melakukan tes pada model ini, model ini bisa mendeteksi sentimen dari bahasa indonesia dengan baik.  


![](https://github.com/naufalmaul/Dokumentasi-Massive/assets/160560916/d2c9af93-4f02-4421-af30-714f60701ada)  

## Integrasi Model Dengan Web HTML

Kami menggunakan flask dan huggingface api token untuk menghosting web ini, ini merupakan Back-End. Kami mengintegrasikan endpoint API ke dalam komponen frontend untuk memungkinkan penggunaan model secara interaktif di dalam website. Dalam Flask, kami dapat menggunakan library “requests” untuk mengirim permintaan HTTP ke API model. Berikut merupakan sebagian kode dari flask:

![](https://github.com/naufalmaul/Dokumentasi-Massive/assets/160560916/4f1372b6-cf05-477e-985f-3b0b3eb852a3)


Kami menggunakan HTML sebagai Front-End Website
![](https://github.com/naufalmaul/Dokumentasi-Massive/assets/160560916/b50a3de8-abd4-4ca7-a75f-68a46389b1c5)


JavaScript digunakan di sisi frontend untuk mengirim data ke backend Flask melalui permintaan HTTP, dilakukan dengan menggunakan metode “fetch”. Di sisi Flask, data yang diterima dari frontend diproses dan hasilnya dikirim kembali ke frontend untuk ditampilkan kepada pengguna. Berikut merupakan kode dari Javascript:
![](https://github.com/naufalmaul/Dokumentasi-Massive/assets/160560916/751a576e-00f0-4d7a-a614-1242a1b3f7db)


Kami menggunakan CSS sebagai Front-End Website
![](https://github.com/naufalmaul/Dokumentasi-Massive/assets/160560916/d5255674-2b4e-4d3c-8900-4941cad03906)



## Our Tech Stacks  
  

<div align="center">  
<a href="https://www.python.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/python-original.svg" alt="Python" height="50" /></a>  
</div>  


## <div align="center">Terima kasih🙏🙏</div>  
