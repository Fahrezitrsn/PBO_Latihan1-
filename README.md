# PBO_Latihan1-

    public class Person {
        public static void main(String[] args) {
            Person person1 = new Person();
            Person person2 = new Person ();

            person1.Nama = "Anton";
            person2.Nama = "Riko";

            person1.JenisKelamin = "Laki-Laki";
            person2.JenisKelamin = "Laki-Laki";

            person1.Umur = 19;
            person2.Umur = 23;

            //Untuk Anton
            System.out.println("Nama: " +person1.Nama+
                               "\nJenisKelamin: " +person1.JenisKelamin+
                               "\nUmur: " +person1.Umur);

            //Untuk Riko
            System.out.println("\nNama: " +person2.Nama+
                               "\nJenisKelamin: " +person2.JenisKelamin+
                               "\nUmur: " +person2.Umur);
        }
        private String Nama;
        private String JenisKelamin;
        private int Umur;
    }

![Tugas 1](https://user-images.githubusercontent.com/115134383/197158889-ccd5e237-9aa1-4356-9f3d-e762a5149343.png)
