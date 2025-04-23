# variable global untuk menyimpan data buku
buku = []

# fungsi untuk menampilkan semua data buku
def show_data():
    if len(buku) <=0:
        print("DATA BUKU BELUM ADA")
    else:
        for indeks in range(len(buku)):
            print("[%d] %s" % (indeks, buku[indeks]))

def insert_data():
    buku_baru = input("judul buku : ")
    buku.append(buku_baru)

def edit_data():
    show_data()
    indeks= int(input("inputkan ID buku : "))
    if(indeks> len(buku)):
        print("ID BUKU TIDAK DITEMUKAN")
    else:
        judul_baru = input("judul baru :")
        buku[indeks] = judul_baru

def delete_data():
    show_data()
    indeks = int(input("inputkan ID buku :"))
    if(indeks > len(buku)):
        print("ID buku tidak ditemukan")
    else:
        buku.remove(buku[indeks])
        print(f"buku dengan ID {indeks}Terhapus")

def show_menu():
    print("\n")
    print(5*"-","MENU", 5*"-")
    print("[1] show data")
    print("[2] insert data")
    print("[3] edit data")
    print("[4] delete data")
    print("[5] exit ")

menu = int(input("PILIH MENU :"))
print("\n")
if menu == 1:
    show_data()
elif menu == 2:
    insert_data()
elif menu == 3:
    edit_data()
elif menu == 4:
    delete_data()
elif menu == 5:
    exit()
else:
    print("Pilihan Anda Salah!") 