<svelte:head>
    <meta name="Apple-mobile-web-app-status-bar-style" content="#742284">
	<meta name="theme-color" content="#742284">
	<meta name="msapplication-TileColor" content="#742284">
    
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="Puedes verificar la aplicación de tu vacuna contra el coronavirus u otras que hayas recibido recientemente en el Carné de vacunación web del Ministerio de Salud. Aquí, está registrada la fecha y lugar donde se te inmunizó, además del tipo de vacuna que recibiste, el fabricante de la vacuna y el número de lote.">
    <meta name="keywords" content="Carnet Vacunas, Minsa, Covid19">
    <meta name="author" content="Minsa Perú">
    <title>MINSA - Carnet Vacunación</title>
    <link id="app-template" rel="stylesheet" href="minsa/app20211210.min.css">
</svelte:head>

<script>
	import { push } from "svelte-spa-router";
</script>

<div class="appiminsa" id="japp">
        <div class="aContainer">
            <div class="text-center">
                <img src="minsa/logo-minsa-opt.jpg" alt="Logo Minsa" width="220" style="max-width: 15rem; width: 100%; border: #fff solid 1px">
            </div>
            <div class="aLogo">
                <img src="minsa/logo-carnet-opt.png" class="aLogoImg" alt="Logo Carnet de Vacunación - MINSA">                
            </div> 
            <div class="text-center" style="padding:2rem 0.5rem">      
                <div><img src="minsa/comprobado.png"></div>
                <div style="font-size:1.2rem; padding:0.5rem; background: rgba(255,255,255, 0.7); line-height: 2rem; color: #1f484a;">
                    <div>FERNANDEZ CARRERA FRANCISCO JAVIER</div>
                    <div> <b>DNI</b> 44XXXX04</div>
                    <div style="color:#3e8d5e"><b>CON TERCERA DOSIS *</b></div>
                </div>
            </div>
            <div style="padding: 0.7rem 0 0.5rem; text-align: center;">
                <div style="font-size: 1rem;padding:0.5rem;background: rgba(255,255,255, 0.7);">* Persona con tres dosis de vacuna contra COVID 19</div>    
            </div>   
            <hr class="aLine1">
            <div class="text-center" style="color:#6c6c6c">
                Copyright © 2021. Desarrollado por la Oficina General de Tecnologías de la Información del Ministerio de Salud | Todos los derechos reservados.                
            </div>            
        </div>
</div>