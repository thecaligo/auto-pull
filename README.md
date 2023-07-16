# auto-pull
Workflow ini akan secara otomatis merestart server Caligo Anda setiap kali Anda memperbarui repositori Github.
## Cara penggunaan
Anda dapat mengcopy file workflow.yml ini dan menaruhnya di dalam repositori Github Anda di dalam folder .github/workflows .

Setelah itu, pergi ke Setting di dalam repositori dan lalu masuk ke Secrets dan buatlah sebuah secret dengan nama `apikey`, kemudian pergi ke [panel](https://portal.caligo.asia). Setelah itu, klik pada API Credentials dan gunakan nilainya sebagai nilai secret tersebut.
Anda juga perlu membuat secret lain dengan nama `server_id` dan nilai dari 8 huruf terakhir URL server Anda.
Sekarang github action seharusnya berfungsi. Untuk mengujinya, lakukan perubahan baru dan push ke repositori.
