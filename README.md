<link rel="stylesheet"  href="https://fonts.googleapis.com/css2?family=Josefin+Sans">   

<style>

body {background-color: #eee;}

  
  .container {
  /* Por defecto en modo fila, uno al lado del otro */
  display: flex;
  flex-flow: row;
  background-color: #dedede;
  height: 15%;
  padding: 2%;
  font-color:white;
  width:90%;
  border-radius:10px;
  margin-top:15px;
}


.item {
  flex: 1 1 auto;  
}


.icono {  
  justify-content: center;
  align-items: center;
  display:flex;
  width: 15%;
}
.icono img {
   
   width: 100%;
}

.agenda {
  background-color: #dedede;
  justify-content: center;
  align-items: center;
  display:flex;
  width: 50%;
  font-size: 25px; 
  font-family: 'Josefin Sans';
  font-color: #fffff;
}
.numero {
  justify-content: center;
  align-items: center;
  display:flex;
  width: 35%;
  font-size: 20px; 
  font-family: 'Josefin Sans';
  font-color: #fffff;
  background-color: #dedede;

}
.ic {
	
	background-color:#a44b21; 
	width:80%; 
	justify-content: center; 
	display:flex; 
	align-items: center; 
	padding:10%;  
	border-radius:10px;
}

.iname_ {
	
background-color:#39464F;
width:40%; 
justify-content: center; 
display:flex; 
align-items: center; 
padding:15%;  
border-radius:10px;
}


.ciname_ {
	
background-color:#39464F; 
width:40%; 
justify-content: center; 
display:flex; 
align-items: center; 
padding:15%;  
border-radius:10px;
}


.ic_ama {
	
	background-color: 	#fdbb17; 
	width:80%; 
	justify-content: center; 
	display:flex; 
	align-items: center; 
	padding:10%;  
	border-radius:10px;
}

.ic_azu {
	
	background-color: 	#0593c3; 
	width:80%; 
	justify-content: center; 
	display:flex; 
	align-items: center; 
	padding:10%;  
	border-radius:10px;
}


.ic_ver {
	
	background-color:#17df9c; 
	width:80%; 
	justify-content: center; 
	display:flex; 
	align-items: center; 
	padding:10%;  
	border-radius:10px;
}
.ic_roj {
	
	background-color: 	#ff2a56; 
	width:80%; 
	justify-content: center; 
	display:flex; 
	align-items: center; 
	padding:10%;  
	border-radius:10px;
}

.ic_nar {
	
	background-color: 	#ff9456; 
	width:80%; 
	justify-content: center; 
	display:flex; 
	align-items: center; 
	padding:10%;  
	border-radius:10px;
}
.ic_cyan {
	
	background-color: 	#61AD68; 
	width:80%; 
	justify-content: center; 
	display:flex; 
	align-items: center; 
	padding:10%;  
	border-radius:10px;
}
.ic_red {
	
	background-color: 	red; 
	width:80%; 
	justify-content: center; 
	display:flex; 
	align-items: center; 
	padding:10%;  
	border-radius:10px;
}
a:link {
  color: #fff;
  text-decoration: none;
}

/* visited link */
a:visited {
  color: #fff;
  text-decoration: none;
}

/* mouse over link */
a:hover {
  color: #fff;
  text-decoration: none;
}

/* selected link */
a:active {
  color: #fff;
  text-decoration: none;
}
  .code {
  /* Por defecto en modo fila, uno al lado del otro */
  display: flex;
  flex-flow: row;
  background-color: #39464F;
  height: 15%;
  padding: 2%;
  font-color:#222;
  width:90%;
  border-radius:10px;
  margin-top:15px;
}
.cagenda {
  background-color: #39464F;
  justify-content: center;
  align-items: center;
  display:flex;
  width: 50%;
  font-size: 25px; 
  font-family: 'Josefin Sans';
  font-color: #fffff;
}
.cnumero {
  justify-content: center;
  align-items: center;
  display:flex;
  width: 35%;
  font-size: 20px; 
  font-family: 'Josefin Sans';
  font-color: #fffff;
  background-color: #39464F;

}
</style>


<script src="https://code.jquery.com/jquery-3.2.1.js"></script>
<script type="text/javascript">
$(document).ready(function() {
    setTimeout(function() {
        $(".content").fadeOut(1000);
    },2000);
});
</script>



<!--div class="content" style="color:#eee; font-size:20px; text-align: center;  margin: auto; position: fixed;    left: 0px;    top: 0px;    width: 100%;    height: 100%;    z-index: 9999;  background-color: #000; opacity: .99; padding-top:30px;">

Apoyanos  y sigue disfrutando de Blackghost.  <br><br> <img src="https://miro.medium.com/max/1600/1*e_Loq49BI4WmN7o9ItTADg.gif" style="width: 190px; height: 150px;"><br><br>
  Cargando Contenido...</div-->

  <!--div style="align: center; background-color: #777555; border-radius: 15px; color: #eeeeee; padding: 5px; width: 98%;">

  </div-->
  
  
  

<center>

  
<a href="go:lasagendas">
<div class="container">  
  <div class="item agenda"><font color="#39464F">Agendas</font></div>
  <div class="item numero"><p class="iname_"><font Style="color:#D3D6DD ; font-size:xx-small;">LaLiga<br>LigaMX<br>Premiere<br>UFC</font></p></div>
  <div class="item icono"><p class="ic_red"><img src="../app/img/icona.png"></p></div>
</div></a>

<a href="go:code-ad"> 
<div class="code">
  <div class="cagenda"><font color="#ddd">Codigo<br>Invitacion</font></div>
  <div class="cnumero"><p class="ciname_"><font Style="color:#D3D6DD ; font-size:small;">KODI</font></p></div>
  <div class="item icono"><p class="ic_cyan"><img src="../app/img/g_code.png"></p></div>
</div></a>

<a href="go:lista-ad">
<div class="container">  
  <div class="item agenda"><font color="#39464F">Listas m3u</font></div>
  <div class="item numero"><p class="iname_"><font Style="color:#D3D6DD ; font-size:small;">IPTV<br>SSIPTV</font></p></div>
  <div class="item icono"><p class="ic_ama"><img src="../app/img/g_mas.png"></p></div>
</div></a>



<a href="go:activar">
<div class="container">  
  <div class="item agenda"><font color="#39464F">Activar Opciones</font></div>
  <div class="item numero"><p class="iname_"><font Style="color:#D3D6DD ; font-size:small;">Apoyanos</font></p></div>
  <div class="item icono"><p class="ic_ver"><img src="../app/img/g_check.png"></p></div>
</div></a>


