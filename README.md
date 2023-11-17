# Membuat Cluster MPI

Pada tutorial ini, kita akan memahami langkah-langkah yang diperlukan untuk membuat sebuah cluster MPI di lingkungan Ubuntu 22.04. Dari instalasi perangkat lunak hingga konfigurasi setiap node dalam cluster, tutorial ini akan memberikan panduan yang komprehensif bagi pemula maupun mereka yang ingin memperdalam pemahaman mereka tentang komputasi paralel.

## Persiapan
<ol>
  <li> Siapkan beberapa komputer. Tentukan satu komputer untuk master dan beberapa komputer untuk worker. </li>
  <li> Pastikan seluruh komputer terhubung dalam satu jaringan (misalnya: terhubung dengan Wifi yang sama). </li>
  <li> Update dan upgrade package ` sudo apt update && sudo apt upgrade ` </li>
  <li> Install beberapa package sebagai utilitas, yaitu ` net-tools ` dan ` vim ` (opsional). </li>
</ol>



