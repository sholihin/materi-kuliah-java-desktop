# Container #

## Frame ##

## Dialog ##

## Applet ##

## Panel ## 

### Latihan Project ###
Agar lebih mudah untuk memahami java desktop, kita akan melakukan latihan pembuatan aplikasi.
Pertama-tama kita buat file baru dengan nama `HaloSwing.java` pada directory `my-app/src/main/java/com/artivisi/project`,

### Kode Program Java ###

```java
// Baris ini untuk penamaan package
package com.artivisi.project;

// Baris ini untuk pemanggilan komponen pada java
import javax.swing.JFrame;
import javax.swing.JOptionPane;

// Baris ini adalah main class
public class HaloSwing {
	public static void main(String[] xx){

// Baris ini adalah method yang akan memang handle frame
		JFrame fr = new JFrame();   	
		fr.setTitle("Halo Swing"); 		
		
// Baris ini adalah method yang akan memang handle dialogbox
		JOptionPane.showMessageDialog(null, "Halo Dialog"); 	
		
		fr.setSize(200,200);
		fr.setVisible(true);
	}
}
```
