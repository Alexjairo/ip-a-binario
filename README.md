# ip-a-binario
convertir una ip a numero binario
<html>

<body>

<div class="navbar-inner">


<h1>

<div class="center sliding"> direccion ip a binario </div>

</h1>

</div>

<div>

<input type ="number"[(ngModel)]="ipvalor1 "placeholder=" primer valor de la ip"/>

<input type ="number"[(ngModel)]="ipvalor2" placeholder=" segundo valor de la ip"/>


<input type ="number"[(ngModel)]="ipvalor3"placeholder=" tercero valor de la ip" />

<input type ="number"[(ngModel)]="ipvalor4" placeholder=" cuarto valor de la ip"/>

</div>

<br>


<div >


<a href="" class="boton_1" (click)="binario()">binario</a>
 
</div>

<br>

<div clas="respuesta">

valor uno :{{uno}}

valor dos :{{dos}}



valor tres :{{tres}}
 
valor cuatro :{{cuatro}}

</div>

</body>

<html>
