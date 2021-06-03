# Remidi-Semester-2_Program-Kasir
    package Encapsulation;

    public class JayaBaru {
    private String Toko;
    private String Merk;
    private String Size;
    private String Warna;
    private String Jenis;
    private String Kategori;
    private String Harga;
    private String Diskon;
    
    public void setToko(String newValue){
        Toko = newValue;
    }
    public void setMerk(String newValue){
        Merk = newValue;
    }
    public void setSize(String newValue){
        Size = newValue;
    }
    public void setWarna(String newValue){
        Warna = newValue;
    }
    public void setJenis(String newValue){
        Jenis = newValue;
    }
    public void setKategori(String newValue){
        Kategori = newValue;
    }
    public void setHarga(String newValue){
        Harga = newValue;
    }
    public void setDiskon(String newValue){
        Diskon = newValue;
    }
    
    
    public String getToko(){
        return Toko;
    }
    public String getMerk(){
        return Merk;
    }
    public String getSize(){
        return Size;
    }
    public String getWarna(){
        return Warna;
    }
    public String getJenis(){
        return Jenis;
    }
    public String getKategori(){
        return Kategori;
    }
    public String getHarga(){
        return Harga;
    }
    public String getDiskon(){
        return Diskon;
    }
    
    
    
    package Encapsulation;
    
    public class main {
    public static void main(String[]args){
        JayaBaru wie = new JayaBaru();
        wie.setToko("Sepatu Jaya Baru");
        wie.setMerk("910, adidas, nike, skechers, puma, reebok, vans, converse, dan fila");
        wie.setSize("25, 26, 27, 28, 29, 30, 31, 32, 33, dan 34");
        wie.setWarna("black, white, gold, silver, orange, green, yellow, blue, red");
        wie.setJenis("cowok dan cewek");
        wie.setKategori("olahraga, lari, santai, dan kantoran");
        wie.setHarga("mulai 200.000, 300.000, 400.000, 500.000, 600.000, 700.000, 800.000 dan 900.000");
        wie.setDiskon("Untuk pembelian 2 pasang sepatu akan mendapatkan diskon 50.000 dan untuk pembelian 3 pasang sepatu diskon 100.000");
        
        System.out.println("Toko "+wie.getToko());
        System.out.println("Merk:"+wie.getMerk());
        System.out.println("Size:"+wie.getSize());
        System.out.println("Warna:"+wie.getWarna());
        System.out.println("Jenis:"+wie.getJenis());
        System.out.println("Kategori:"+wie.getKategori());
        System.out.println("Harga:"+wie.getHarga());
        System.out.println("Diskon "+wie.getDiskon());
    }
    
    //output
    
    Toko Sepatu Jaya Baru
    Merk:910, adidas, nike, skechers, puma, reebok, vans, converse, dan fila
    Size:25, 26, 27, 28, 29, 30, 31, 32, 33, dan 34
    Warna:black, white, gold, silver, orange, green, yellow, blue, red
    Jenis:cowok dan cewek
    Kategori:olahraga, lari, santai, dan kantoran
    Harga:mulai 200.000, 300.000, 400.000, 500.000, 600.000, 700.000, 800.000 dan 900.000
    Diskon Untuk pembelian 2 pasang sepatu akan mendapatkan diskon 50.000 dan untuk pembelian 3 pasang sepatu diskon 100.000
    BUILD SUCCESSFUL (total time: 0 seconds)
