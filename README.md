# Manav Kasa Programı
Bu program alınan ürünlerin kg fiyatına göre hesaplayıp kaç TL tuttuğunu hesaplar.
## Programın Kodunun Fotoğrafı
![kodlar](images/kodlar.png)

## Programın Fotoğrafı
![program](images/program.png)

'''
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        double armut_fyt=2.14,elma_fyt=3.67, domates_fyt=1.11, muz_fyt=0.95, patlican_fyt=5.0;
        double armut_kg, elma_kg, domates_kg, muz_kg, patlican_kg, toplam;

        Scanner inp=new Scanner(System.in);
        System.out.print("Kac kg armut ? : ");
        armut_kg=inp.nextDouble();

        System.out.print("Kac kg elma ? : ");
        elma_kg= inp.nextDouble();

        System.out.print("Kac kg domates ? : ");
        domates_kg=inp.nextDouble();

        System.out.print("Kac kg muz ? : ");
        muz_kg=inp.nextDouble();

        System.out.print("Kac kg patlican ? : ");
        patlican_kg=inp.nextDouble();

        toplam=(armut_fyt*armut_kg)+(elma_fyt*elma_kg)+(domates_fyt*domates_kg)+(muz_fyt*muz_kg)+(patlican_fyt*patlican_kg);
        System.out.println("Toplam odeyeceginiz tutar: "+toplam+" TL");
    }
}

'''
