
# nama: ELSA ZAHRA IRAIHAN
# kelas: IE.23.C.13
# nim: 352310941	

# latihan 1
![Screenshot (171)](https://github.com/user-attachments/assets/753378a7-ab9c-4d5e-a380-bd1225e0c6c1)

# input


    Nested for loop to generate the pattern
    for i in range(10):  # outer loop for rows
        for j in range(10):  # inner loop for columns
            print(i + j, end=" ")  # print the sum of the indices with a space
        print()  # move to the next line after each row
  ![ss1](https://github.com/user-attachments/assets/771aff22-393b-4833-a874-f3e1e3889530)
  
# output
![Screenshot (173)](https://github.com/user-attachments/assets/b789723a-128d-4e1c-9a5e-f064be7b349b)

# latihan 2
![Screenshot (172)](https://github.com/user-attachments/assets/39cad85e-f640-402e-a5b7-ad51a1d53905)

# input
    import random

    #Meminta pengguna memasukkan nilai n
    n = int(input("Masukkan jumlah n: "))

    #Menginisialisasi variabel untuk menghitung jumlah bilangan acak
    count = 0

    #Menggunakan while untuk terus menghasilkan bilangan acak sampai mencapai jumlah n
    while count < n:
        #Menghasilkan bilangan acak kurang dari 1
        random_number = random.random()
    
    # Jika bilangan acak kurang dari 0.5, maka cetak dan tambahkan ke count
    if random_number < 0.5:
        print(random_number)
        count += 1
![ss2](https://github.com/user-attachments/assets/9f3a7d25-f35c-4e63-b6f6-29961334ac24)

# output
![Screenshot (174)](https://github.com/user-attachments/assets/75f72632-0613-41d9-8a1e-f4aa1250d204)


