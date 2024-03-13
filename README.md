# Advanced Programming Course Tutorial

### Nama   : Muhammad Nabiel Subhan
### NPM    : 2206081553
### Kelas  : AdPro B

## Tutorial 5

### Before Optimization
- /all-student
<p align="center">
  <img src="src\main\resources\static\images\before-all-student.png" />
</p>
<p align="center">
  <img src="src\main\resources\static\images\before-testresults1.png" />
</p>
- /all-student-name
<p align="center">
  <img src="src\main\resources\static\images\before-all-student-name.png" />
</p>
<p align="center">
  <img src="src\main\resources\static\images\before-testresults2.png" />
</p>
- /highest-gpa
<p align="center">
  <img src="src\main\resources\static\images\before-highest-gpa.png" />
</p>
<p align="center">
  <img src="src\main\resources\static\images\before-testresults3.png" />
</p>

### After Optimization
- /all-student
<p align="center">
  <img src="src\main\resources\static\images\after-all-student.png" />
</p>
<p align="center">
  <img src="src\main\resources\static\images\after-testresults1.png" />
</p>
- /all-student-name
<p align="center">
  <img src="src\main\resources\static\images\after-all-student-name.png" />
</p>
<p align="center">
  <img src="src\main\resources\static\images\after-testresults2.png" />
</p>
- /highest-gpa
<p align="center">
  <img src="src\main\resources\static\images\after-highest-gpa.png" />
</p>
<p align="center">
  <img src="src\main\resources\static\images\after-testresults3.png" />
</p>

Dapat dilihat antara sebelum dan sesudah *optimization*, waktu yang dibutuhkan untuk mengakses tiap *endpoint* berkurang secara signifikan setelah dilakukan proses *optimization*. Hal ini menunjukkan bahwa proses *optimization* yang dilakukan telah meningkatkan kinerja program khususnya dari segi waktu untuk mengakses tiap *endpoint* tersebut.

1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
  - JMeter
    Dengan menggunakan JMeter, kita dapat mensimulasikan *load* pada sebuah aplikasi dan mengukur kinerjanya dari segi waktu respons, throughput, dan konkurensi. Kita juga dapat mengidentifikasi *bottleneck* pada kinerja aplikasi, tetapi JMeter tidak memberikan secara rinci penyebab dari *bottleneck* tersebut.

   - IntelliJ Profiler
     Dengan menggunakan IntelliJ Profiler, kita dapat menganalisis perilaku aplikasi secara lebih detail sehingga memudahkan kita untuk mengetahui bagian mana pada kode kita yang memakan waktu lama. Dengan begitu, kita dapat langsung mengoptimalkan bagian kode secara spesifik yang menyebabkan masalah pada kinerja program.

2. How does the profiling process help you in identifying and understanding the weak points in your application?

Proses profiling memberikan berbagai informasi, seperti CPU time untuk setiap method, aktivitas thread, penggunaan sumber daya memori, dan lain-lain. Dari informasi-informasi tersebut kita dapat mengidentifikasi bagian spesifik di kode kita yang memengaruhi kinerja program secara signifikan sehingga memudahkan kita untuk mengetahui bagian mana yang perlu dioptimalkan.

3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?

Ya, IntelliJ Profiler sangat membantu saya untuk menemukan bagian kode yang menimbulkan masalah pada kinerja program saya. Dengan menggunakan IntelliJ Profiler, saya dapat mengidentifikasi 3 method yang perlu dilakukan optimasi untuk meningkatkan kinerja program, yaitu pada method getAllStudentsWithCourses, findStudentWithHighestGpa, dan joinStudentNames.

4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?

Tantangan yang saya temukan adalah kurangnya pemahaman dalam menggunakan profiler dan kesulitan dalam membaca hasil pengujiannya. Namun, dengan mengikuti tutorial dan mengerjakan exercise membuat saya menjadi sedikit terbiasa dengan menggunakan profiler dan membantu saya dalam melakukan analisis dari hasil pengujian tersebut.

5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?

Keuntungan utama yang saya dapatkan dari menggunakan IntelliJ Profiler adalah mengetahui bagian kode mana secara spesifik yang memberikan masalah secara signifikan kepada kinerja program.

6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?

Jika terdapat hasil yang tidak konsisten, yang mungkin akan saya lakukan adalah menganalisis perbedaan yang terjadi, seperti membandingkan metrik-metrik yang diukur. Selain itu, perlu juga dilakukan *cross check* kembali terkait prosedur *performance testing* yang sebelumnya telah dilakukan, apakah sudah dilakukan dengan benar atau belum. Setelah itu, dilakukan *re-testing* untuk memastikan kembali.

7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?

Ketika sudah mengetahui bagian kode mana yang menyebabkan masalah, saya akan berusaha untuk memahami apa yang kode tersebut lakukan terlebih dahulu, seperti *output* apa yang akan dihasilkan oleh kode tersebut. Hal ini penting untuk dilakukan demi menjaga konsistensi fungsionalitas program. Selain itu, saya juga perlu untuk memahami cara kerja kode secara keseluruhan agar mengetahui method-method apa saja yang sudah ada dan nantinya dapat dijadikan pertimbangan ketika melakukan proses pengoptimalan kode.
  
