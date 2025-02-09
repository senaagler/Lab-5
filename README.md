# Lab-5
Letter
package lab_2;

import java.util.Scanner;

public class lab_3 {

	public static void main(String[] args) {

 
 Scanner scanner = new Scanner(System.in);  

  System.out.println("Lütfen bir paragraf giriniz:");  
 String paragraf = scanner.nextLine();  

  int aSayisi =0;  
 int buyukHarfSayisi =0;  

 for (int i =0; i < paragraf.length(); i++) {  
 char ch = paragraf.charAt(i);  

  if (ch == 'a') {  
 aSayisi++;  
 }  

 if (Character.isUpperCase(ch)) {  
 buyukHarfSayisi++;  
 }  
 }  

 System.out.println("Paragraftaki 'a' karakterinin sayısı: " + aSayisi);  
 System.out.println("Paragraftaki büyük harf sayısı: " + buyukHarfSayisi);  
 
 
 
 
 


	        String ders = "Java Programlama Dersi Fall 2024";
	        int baslangicIndex = ders.indexOf("Programlama Dersi");
	        
	        if (baslangicIndex != -1) {
	            String yeniDers = ders.substring(0, baslangicIndex) + ders.substring(baslangicIndex + "Programlama Dersi ".length());
	            System.out.println(yeniDers);
	            
	            
	        } else {
	            System.out.println("Belirtilen metin bulunamadı.");
	        }
	    
  scanner.close();  
 }  
	
	

		

	}


