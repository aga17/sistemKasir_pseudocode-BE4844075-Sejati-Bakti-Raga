# Sejati Bakti Raga - BE4844075
# FLOW CHART SISTEM KASIR (memasukan item dan auto calculate harga).

```
START
    DECLARE total_harga = 0
    WHILE customer masih ingin membeli
        READ nama_barang
        READ harga_barang
        READ jumlah_barang
        total_harga = total_harga + (harga_barang * jumlah_barang)
        PRINT "Anda ingin membeli barang lagi? (Ya/Tidak)"
        READ customer_input
        IF customer_input = "Tidak"
            BREAK
        END IF
    END WHILE
    PRINT "Total harga: " + total_harga
END
```
