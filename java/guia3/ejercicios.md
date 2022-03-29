# Ejercicio 1
````java
import javax.swing.JOptionPane;


public class Main {
	
	public static void main(String[] args) {
		
		double promedio;
		
		promedio=Double.parseDouble(JOptionPane.showInputDialog("Digite el promedio de alumno: "));
		
		if(promedio>=17)
		{
			JOptionPane.showInternalMessageDialog(null, "Categoria A");
		}
		else if(promedio>=14&&promedio<17)
		{
			JOptionPane.showMessageDialog(null, "Categoria A");
		}
		else if(promedio>=12&&promedio<14)
		{
			JOptionPane.showMessageDialog(null,"Categoria B");
		}
		else if(promedio>=12&&promedio<14)
		{
			JOptionPane.showMessageDialog(null,"Categoria C");
		}
		else if(promedio<12)
		{
			JOptionPane.showMessageDialog(null, "Categoria D");
		}
	}
}
````

# Ejercicio 2
````java
import javax.swing.JOptionPane;


public class Main {
	public static void main(String[] args) {
		
		//cantidad_litros lo paso como double para poder hacer los calculos
		double cantidad_litros=Double.parseDouble(JOptionPane.showInputDialog("Ingrese la cantidad de litros: "));
		
		double Precio_litro,descuento,importe_compra,importe_pagar,desc=0;
		
		String Codigo=JOptionPane.showInputDialog("Ingrese el codigo: ");
		
		
		Codigo.toLowerCase();
		
		if(Codigo.compareTo("primor")==0)
		{
			Precio_litro=5.99;
			importe_compra=Precio_litro*cantidad_litros;
			desc=descuento(importe_compra,cantidad_litros);
			importe_pagar=importe_compra-desc;
			JOptionPane.showMessageDialog(null,"Importe de compra: "+importe_compra);
			JOptionPane.showMessageDialog(null, "El descuento es: "+desc);
			JOptionPane.showMessageDialog(null, "Importe a pagar: "+importe_pagar);
		}
		else if(Codigo.compareTo("girasol")==0)
		{
			Precio_litro=5.50;
			importe_compra=Precio_litro*cantidad_litros;
			desc=descuento(importe_compra,cantidad_litros);
			importe_pagar=importe_compra-desc;
			JOptionPane.showMessageDialog(null,"Importe de compra: "+importe_compra);
			JOptionPane.showMessageDialog(null, "El descuento es: "+desc);
			JOptionPane.showMessageDialog(null, "Importe a pagar: "+importe_pagar);
		
		}
		else if(Codigo.compareTo("cil")==0)
		{
			Precio_litro=4.50;
			importe_compra=Precio_litro*cantidad_litros;
			desc=descuento(importe_compra,cantidad_litros);
			importe_pagar=importe_compra-desc;
			JOptionPane.showMessageDialog(null,"Importe de compra: "+importe_compra);
			JOptionPane.showMessageDialog(null, "El descuento es: "+desc);
			JOptionPane.showMessageDialog(null, "Importe a pagar: "+importe_pagar);
			
		}
		else if(Codigo.compareTo("cocinero")==0)
		{
			Precio_litro=4.70;
			importe_compra=Precio_litro*cantidad_litros;
			desc=descuento(importe_compra,cantidad_litros);
			importe_pagar=importe_compra-desc;
			JOptionPane.showMessageDialog(null,"Importe de compra: "+importe_compra);
			JOptionPane.showMessageDialog(null, "El descuento es: "+desc);
			JOptionPane.showMessageDialog(null, "Importe a pagar: "+importe_pagar);
		}
		else
		{
			JOptionPane.showMessageDialog(null, "Esa marca no existe ");
		}
	}
    public static double descuento(double  importe_compra,double cantidad_litros)
	{
		//se inicializo en 0 por que daba error
		double desc=0;
		//No se hizo en funcion por que salia un error de valor
		if(cantidad_litros>=10)
		{
			desc=importe_compra*0.075;
		}
		else if(cantidad_litros>=7&&cantidad_litros<10)
		{
			 desc=importe_compra*0.10;
		}
		else if(cantidad_litros>=4&&cantidad_litros<7)
		{
			 desc=importe_compra*0.075;
		}
		else if(cantidad_litros<4)
		{
			 desc=importe_compra*0.05;
		}
		return desc;
	}
}
````

# Ejercicio 3
````java
import javax.swing.JOptionPane;


public class Main {
	public static void main(String[] args) {
		
		//cantidad_litros lo paso como double para poder hacer los calculos
		double cantidad_litros=Double.parseDouble(JOptionPane.showInputDialog("Ingrese la cantidad de litros: "));
		
		double Precio_litro,descuento,importe_compra,importe_pagar,desc=0;
		
		String Codigo=JOptionPane.showInputDialog("Ingrese el codigo: ");
		
		
		Codigo.toLowerCase();
		
		if(Codigo.compareTo("laive")==0)
		{
			Precio_litro=3.90;
			importe_compra=Precio_litro*cantidad_litros;
			desc=descuento(importe_compra,cantidad_litros);
			importe_pagar=importe_compra-desc;
			JOptionPane.showMessageDialog(null,"Importe de compra: "+importe_compra);
			JOptionPane.showMessageDialog(null, "El descuento es: "+desc);
			JOptionPane.showMessageDialog(null, "Importe a pagar: "+importe_pagar);
		}
		else if(Codigo.compareTo("gloria")==0)
		{
			Precio_litro=3.80;
			importe_compra=Precio_litro*cantidad_litros;
			desc=descuento(importe_compra,cantidad_litros);
			importe_pagar=importe_compra-desc;
			JOptionPane.showMessageDialog(null,"Importe de compra: "+importe_compra);
			JOptionPane.showMessageDialog(null, "El descuento es: "+desc);
			JOptionPane.showMessageDialog(null, "Importe a pagar: "+importe_pagar);
		
		}
		else if(Codigo.compareTo("pura vida")==0)
		{
			Precio_litro=4.20;
			importe_compra=Precio_litro*cantidad_litros;
			desc=descuento(importe_compra,cantidad_litros);
			importe_pagar=importe_compra-desc;
			JOptionPane.showMessageDialog(null,"Importe de compra: "+importe_compra);
			JOptionPane.showMessageDialog(null, "El descuento es: "+desc);
			JOptionPane.showMessageDialog(null, "Importe a pagar: "+importe_pagar);
			
		}
		else if(Codigo.compareTo("milkito")==0)
		{
			Precio_litro=3.60;
			importe_compra=Precio_litro*cantidad_litros;
			desc=descuento(importe_compra,cantidad_litros);
			importe_pagar=importe_compra-desc;
			JOptionPane.showMessageDialog(null,"Importe de compra: "+importe_compra);
			JOptionPane.showMessageDialog(null, "El descuento es: "+desc);
			JOptionPane.showMessageDialog(null, "Importe a pagar: "+importe_pagar);
		}
		else
		{
			JOptionPane.showMessageDialog(null, "Esa marca no existe ");
		}
	}
	//los parametros tienen que ser igual a lo que el programa devuelve
    public static double descuento(double  importe_compra,double cantidad_litros)
	{
		//se inicializo en 0 por que daba error
		double desc=0;
		//No se hizo en funcion por que salia un error de valor
		if(cantidad_litros<=15)
		{
			desc=importe_compra*0.04;
		}
		else if(cantidad_litros>=15&&cantidad_litros<30)
		{
			 desc=importe_compra*0.065;
		}
		else if(cantidad_litros>=30&&cantidad_litros<45)
		{
			 desc=importe_compra*0.09;
		}
		else if(cantidad_litros>=45)
		{
			 desc=importe_compra*0.115;
		}
		return desc;
	}
}
````

# Ejercicio 4
````java
import javax.swing.JOptionPane;


public class Main {
	
	public static void main(String[] args) {

        double peso_kg,estatura,imc;
		
		peso_kg=Double.parseDouble(JOptionPane.showInputDialog("Ingrese su peso en kilogramos: "));
		
		estatura=Double.parseDouble(JOptionPane.showInputDialog("Ingrese su estatura en metros: "));
		
		imc=peso_kg/(estatura*estatura);
		
		JOptionPane.showMessageDialog(null, "Su indice de masa corporal: "+imc);
		
		if(imc<20)
		{
			JOptionPane.showInternalMessageDialog(null, "Delgado");
		}
		else if(imc>=20&&imc<25)
		{
			JOptionPane.showMessageDialog(null, "Normal");
		}
		else if(imc>=25&&imc<27)
		{
			JOptionPane.showMessageDialog(null,"Sobrepeso");
		}
		else if(imc>=27)
		{
			JOptionPane.showMessageDialog(null,"Obesidad");
		}
	}
}
````
