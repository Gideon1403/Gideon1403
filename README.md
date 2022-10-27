
#mebuat varbel nama barang
#mebuat varbel harga barang
#mebuat varbel persen barang
#input nama barang
#input harga barang 
#menghitung harga barang
#harga barang * persen / 100
#print harga beserta nama barang


modal_keseluruhan = 0
laba_keseluruhan = 0
while(True):
    Nama_barang = input ('masukan nama barang : ')
    harga_barang = input('masukan harga barang : ')
    persen_harga = input ('masukan persen barang: ')
    barang_terjual = input ('masukan jumblah barng terjual: ') 

    keuntuungan_persen = = haraga_barang * persen / 100
    harga_jual = harga_barang + keuntuungan_persen

    # menghitung modal
    modal = haraga_barang * barang_terjual
    # menghitung modal keseluruhan
    modal_keseluruhan = modal_keseluruhan + modal

    # menghitung laba
     laba = keuntuungan_persen * barang_terjual
    # menghitung modal keseluruhan
    laba_keseluruhan = modal_keseluruhan + laba
    
    print (Nama_barang, "dijual dengan  harga: ")
    print ('dengan modal : Rp.' , harga_barang)
    print ('dengan keuntungan : Rp' , harga_keuntuungan)


    apakah_lanjut = input ('apakah ingin input barang lain? Y untuk ya dan N untuk no : ')
    if(apakah_lanjut != "Y"):
       break
