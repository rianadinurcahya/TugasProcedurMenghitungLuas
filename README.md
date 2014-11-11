TugasProcedurMenghitungLuas
===========================

package id.blits.Tugas;


public class NewMainMenu {

 
    public static void main(String[] args) {
        // TODO code application logic here
        PersegiPanjang PerPan =  new  PersegiPanjang();
        PerPan.nama="Persegi Panjang";
        PerPan.Panjang=20;
        PerPan.Lebar=10;
        
        PerPan.tampilPersegiPanjang();
        
        Segitiga St = new Segitiga();
        St.nama="Menghitung Luas Segi Tiga";
        St.Alas=50;
        St.Tinggi=100;
        
        St.tampilSegiTiga();
        
        Lingkaran Lingk = new  Lingkaran();
        Lingk.nama="Menghitung Luas Lingkaran";
        Lingk.Jari2=8;
        
        Lingk.tampilLingkaran();

        

        
    }
    
}
