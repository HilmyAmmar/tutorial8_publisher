# Tutorial 8
### How many data your publlsher program will send to the message broker in one run?
Program akan mengirim 5 pesan ke *message broker*
### The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
URL tersebut merupakan alamat dari *message broker*. "amqp://" menandakan bahwa alamat 
menggunakan protokol AMQP. Sama seperti penjelasan di bagian subscriber, "guest:guest@localhost:5672" 
menentukan bahwa *message broker* berjalan di mesin lokal pada port 5672.
