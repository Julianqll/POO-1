# Ejercicio 1
```
import javax.swing.JOptionPane;


public class Main {
	
	public static void main(String[] args) {
		
		double area,perimetro,altura,base;
		
		base=Double.parseDouble(JOptionPane.showInputDialog("Ingrese la base: "));
		altura=Double.parseDouble(JOptionPane.showInputDialog("Ingrese la altura: "));
		
		area=base*altura;
		
		perimetro=2*(base + altura);
		
		
		JOptionPane.showMessageDialog(null, "El area del rectangulo es: "+area);
		JOptionPane.showMessageDialog(null, "El perimetro del rectangulo es: "+perimetro);	
	}
}    
```
# Ejercicio2

```
import javax.swing.JOptionPane;


public class Main {
	
	public static void main(String[] args) {
		
		double areabase,radio,areatotal,altura,arealateral;
		radio=Double.parseDouble(JOptionPane.showInputDialog("Ingrese el radio: "));
		altura=Double.parseDouble(JOptionPane.showInputDialog("Ingrese la altura: "));
		
		areabase=3.1416*(radio*radio);
		
		arealateral=2*3.1416*radio*altura;
		
		areatotal=2*(areabase)+arealateral;
		
		JOptionPane.showMessageDialog(null, "El area lateral es: "+arealateral);
		JOptionPane.showMessageDialog(null, "El area total: "+areatotal);	
		JOptionPane.showMessageDialog(null, "El area de la base: "+areabase);
	}
}
```
# Ejercicio 3

```
import javax.swing.JOptionPane;


public class Main {
	
	public static void main(String[] args) {
		
		int edad_años;
		
		double peso_kg,frecuencia;
		
		peso_kg=Double.parseDouble(JOptionPane.showInputDialog("Ingrese su peso en kilogramos: "));
		
		edad_años=Integer.parseInt(JOptionPane.showInputDialog("Ingrese su cantidad de años"));
		
		frecuencia=210-(0.5*edad_años)-((0.01*peso_kg)+4);
		
		JOptionPane.showMessageDialog(null, "La frecuencia cardiaca de la persona: "+frecuencia);

	}
}
```

# Ejercicio 4

```
import javax.swing.JOptionPane;


public class Main {
	
	public static void main(String[] args) {
		
		double peso_kg,estatura,imc;
		
		peso_kg=Double.parseDouble(JOptionPane.showInputDialog("Ingrese su peso en kilogramos: "));
		
		estatura=Double.parseDouble(JOptionPane.showInputDialog("Ingrese su estatura en metros: "));
		
		imc=peso_kg/(estatura*estatura);
		
		JOptionPane.showMessageDialog(null, "Su indice de masa corporal: "+imc);
	}
}
```

# Ejercicio 5

```
import javax.swing.JOptionPane;


public class Main {
	
	public static void main(String[] args) {
		
		double promedio,p1,p2,ep,ef;
		p1=Double.parseDouble(JOptionPane.showInputDialog("Ingrese la nota de su practica 1: "));
		p2=Double.parseDouble(JOptionPane.showInputDialog("Ingresa la nota de la practica 2: "));
		ep=Double.parseDouble(JOptionPane.showInputDialog("Ingrese la nota del examen parcial: "));
		ef=Double.parseDouble(JOptionPane.showInputDialog("Ingrese la nota del examen final: "));

		promedio=(0.10*p1)+(0.10*p2)+(0.35*ep)+(0.45*ef);
		
		JOptionPane.showMessageDialog(null, "El promedio: "+ promedio);
	}
}
```
