# Taksimetre

int km;
double perKM = 2.2, total, acilisFiyati = 10;

Scanner scanner = new Scanner(System.in);

System.out.println("KM Giriniz: ");
km = scanner.nextInt();

total = km * perKM;
total += acilisFiyati;

total = (total < 20) ? 20 : total;

System.out.println("Toplam Tutar: " + total);
