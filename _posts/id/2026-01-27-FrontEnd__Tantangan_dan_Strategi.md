---
ref: FrontEnd__Tantangan_dan_Strategi
judul: 'FrontEnd: Tantangan dan Strategi'
title: 'FrontEnd: Tantangan dan Strategi'
description: ''
tags: [idea]
category: Idea
category_url: idea
---

# FrontEnd: Tantangan dan Strategi

Situasi:

saya mempunyai system yang cukup kompleks {[link](/id/Data_Model_part_1__Entity_DTO_Data_Transfer_Object/)}
- lebih dari 500 table
- FrontEnd mempunyai Tantangan tersendiri

Secara garis besar, ada 2 Team:
- Team A
  - Design - Business Process
    - file Dokumentasi
  - Design - UI, menggunakan:
    - [figma.com](https://www.figma.com/)
    - [moqups.com](https://moqups.com/)
- Team X
  - Developer
 
> catatan: saya menulis artikel ini, dengan semangat [Menulis untuk 'Future of Me'](/id/Menulis-untuk-Future-of-Me/)

## Strategi

Untuk membuat irama kerja yang smooth, saya memerlukan suatu pedoman:
- membuat beberapa _Task Besar_, dengan tujuan yang spesifik
- CI / CD {Continuous Improvement / Continuous Development}

### FrontEnd

- HTML
  - _convert_ Design - UI ke HTML
  - bisa dengan menggunakan Tools di atas
  - atau [Request: ke AI secara efektif dan efisien {Tone yang tepat}](/id/Request_ke_AI_secara_efektif_dan_efisien__Tone_yang_tepat/)
- JavaScript
  - bagian untuk _handle_ HTML
  - bagian untuk _connect_ ke _end-point_ di `BackEnd`

### BackEnd

- Part 1: Read Data
  - data Simple {contoh: data untuk _Dropdown_}
  - data berupa _Tabular_
  - menggunakan teknik sesuai artikel [Data Model part 2 - DTO {Data Transfer Object}](/id/Data_Model_part_2__DTO_Data_Transfer_Object/)
- Part 2: CRUD
  - data Simple
  - data _Header - Detail_
  - data dengan kolom berupa `JSON format`
- Part 3:
  - bagian _BackEnd_ yang merupakan implementasi _Design - Business Process_

> catatan untuk _BackEnd_:
> - masing-masing Part dibuat untuk menghindari "stuck" pada _BackEnd_ -- secara keseluruhan
> - bisa dimulai dari yang paling mudah:
>     - seringkali yang _urgent_ diperlukan: bagian _BackEnd_ untuk "Read Data" saja
>     - sedangkan bagian _BackEnd_ yang lebih kompleks {implementasi _Design - Business Process_}, bisa dibuat berikutnya

## Untuk User / Client

Pada akhirnya, semua ini dibangun untuk satu tujuan:
> sebuah Product yang benar-benar berfungsi — untuk User/Client yang menggunakannya.

Itulah GOAL-nya.<br/>
Ketika ragu dalam mengambil keputusan, kembali ke GOAL tersebut.<br/>
<br/>
SDR:<br/>
**S** {Situation → Specific → Simple → Speed → **Shipment**}<br/>
**D** {Define → Design → Document → Develop → **Delivery**}<br/>
**R** {Realistic → Refine → **Result**}
